<template>
  <nav :class="headerClassList" class="fixed w-full z-30 top-0 header___bar">
    <div
      class="
        w-full
        container
        flex flex-wrap
        items-center
        justify-between
        mt-0
        py-2
        mx-auto
      "
    >
      <div class="pl-4 flex items-center">
       <h1 class="font-bold text-2xl text-black">Emilson-Blog</h1>
      </div>
      <div class="block lg:hidden pr-4">
        <span
          class="flex items-center p-1 text-black hover:text-gray-900"
          @click.prevent.stop="onToggleClick"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-8 w-8"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h16m-7 6h7"
            />
            <title>Menu</title>
          </svg>
        </span>
      </div>

      <div
        :class="navContentClassList"
        class="
          w-full
          flex-grow
          lg:flex lg:items-center lg:w-auto lg:block
          mt-2
          lg:mt-0
          bg-white
          lg:bg-transparent
          text-black
          p-4
          lg:p-0
          z-20
        "
      >
        <ul class="list-reset lg:flex justify-end flex-1 items-center">
          <li class="mr-3">
            <a
              class="
                inline-block
                text-black
                no-underline
                hover:text-gray-800 
                py-2
                px-4
              "
              href="#"
              ><router-link to="/">HTML TOPICS</router-link></a
            >
          </li>

          <li class="mr-3">
            <a
              class="
                inline-block
                text-black
                no-underline
                hover:text-gray-800 
                py-2
                px-4
              "
              href="#"
              >CSS TOPICS</a
            >
          </li>
          <li class="mr-3">
            <a
              class="
                inline-block
                text-black
                no-underline
                hover:text-gray-800 
                py-2
                px-4
                uppercase
              "
              href="#"
              ><router-link to="/">Javascript TOPICS </router-link></a
            >
          </li>
          <li class="mr-3">
            <a
              class="
                inline-block
                text-black
                no-underline
                hover:text-gray-800 
                py-2
                px-4
                uppercase
              "
              href="#"
              ><router-link to="/">VueJS Topics</router-link></a
            >
          </li>
          <li class="mr-3">
            <a
              class="
                inline-block
                text-black
                no-underline
                hover:text-gray-800 
                py-2
                px-4
                uppercase
              "
              href="#"
              ><router-link to="">Other Topics</router-link></a
            >
          </li>

          <template>
            <li class="mr-3">
              <a
                class="
                  inline-block
                  text-black
                  shadow-2xl
                  btn-sign
                  px-10
                  no-underline
                  
                  py-3
                  md:mx-6
                "
                href="#"
                ><router-link to="/"> Start Free Trial </router-link></a
              >
            </li>
          </template>
        </ul>
      </div>
    </div>
    <hr class="border-b border-gray-100 opacity-25 my-0 py-0" />
  </nav>
</template>

<script>

export default {
  name: "NavBar",
 
  data() {
    return {
      scrollY: 0,
      isOpen: false,
    };
  },
  computed: {
   
    isSticky() {
      return this.scrollY > 10;
    },
    headerClassList() {
      return this.isSticky ? "bg-white shadow" : "";
    },
    navActionClassList() {
      return this.isSticky ? "gradient text-white" : "bg-white text-gray-800";
    },
    navContentClassList() {
      let classList = this.isSticky ? "bg-white" : "bg-gray-100";
      if (!this.isOpen) {
        classList += ` hidden`;
      }
      return classList;
    },
  },
  methods: {
    onClick() {
      this.isOpen = false;
    },
    onScroll() {
      this.scrollY = window.scrollY;
    },
    onToggleClick() {
      this.isOpen = !this.isOpen;
    },
  },
  mounted() {
    this.scrollY = window.scrollY;
    document.addEventListener("click", this.onClick);
    document.addEventListener("scroll", this.onScroll);
  },
  beforeDestroy() {
    document.removeEventListener("click", this.onClick, true);
    document.removeEventListener("scroll", this.onScroll, true);
  },
};
</script>
<style scoped>
.btn-sign {
  background-color: #0c0e2d;
  border-radius: 4px;
}
</style>
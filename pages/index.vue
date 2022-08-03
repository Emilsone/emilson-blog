<!-- ./pages/index.vue -->
<template>
  <main>
    <section
      class="
        hero-section
        flex
        items-center
        justify-center
        text-center
        w-full
        h-screen
        
      "
    >
      <header>
        <h1 class="font-black text-8xl">Emilson Technical Blog</h1>
      </header>
    </section>
    <section class="body-font">
      <div
        class="
          container
          mx-auto
          flex
          px-5
          py-24
          md:flex-row
          flex-col
          items-center
        "
      >
        <div
          class="
            lg:flex-grow
            md:w-1/2
            lg:pr-24
            md:pr-16
            flex flex-col
            md:items-start md:text-left
            mb-16
            md:mb-0
            items-center
            text-center
          "
        >
          <h1 class="title-font sm:text-4xl text-3xl mb-4 font-bold text-black">
            About Me
          </h1>
          <p class="mb-8 leading-relaxed text-black">
            I'm currently a technical writer and software developer. Aside from
            building web tools and applications, I realized that I'd want to do
            more than build. I'd also want to share resources, teach online, and
            guide developers. I enjoy educating people and simplifying
            complicated issues for their easy understanding.
          </p>
          <div class="flex justify-center">
            
          
          </div>
        </div>
        <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
          <img
            class="object-cover object-center rounded"
            alt="hero"
            src="https://dummyimage.com/720x600"
          />
        </div>
      </div>
    </section>

    <!-- ARTICLE SECTION -->

    <section class="article-section body-font">
      <div class="container px-5 py-24 mx-auto">
        <h4 class="sm:text-2xl text-3xl mb-4 font-bold text-black">
          I have written lot of articles for different blog
        </h4>
        <div class="flex flex-wrap -m-4">
          <div class="p-4 lg:w-1/3">
            <div
              class="
                h-5/6
                px-8
                pt-16
                pb-24
                rounded-sm
                overflow-hidden
                relative
                article-card
              "
            >
              <h2
                class="
                  tracking-widest
                  text-xs
                  title-font
                  font-medium
                  text-black
                  mb-4
                  inline-block
                  py-1
                  px-2
                  rounded
                  bg-white
                "
              >
                Javascipt | Currying
              </h2>
              <h1
                class="title-font sm:text-3xl text-xl font-bold text-black mb-3"
              >
                Understanding JavaScript currying
              </h1>
              <p class="leading-relaxed mb-3 text-black">
                In this article, we’re going to explore what currying is in
                Javascript, why and where you should use currying, and how to
                implement it with code examples.
              </p>
              <a class="text-black  inline-flex items-center"
                >Read More
                <svg
                  class="w-4 h-4 ml-2"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                >
                  <path d="M5 12h14"></path>
                  <path d="M12 5l7 7-7 7"></path>
                </svg>
              </a>
              <div
                class="
                  text-center
                  mt-2
                  leading-none
                  flex
                  justify-center
                  absolute
                  bottom-0
                  left-0
                  w-full
                  py-4
                "
              >
              
              </div>
            </div>
          </div>
          <div class="p-4 lg:w-1/3">
            <div
              class="
                h-5/6
                px-8
                pt-16
                pb-24
                rounded-sm
                overflow-hidden
                relative
                article-card
              "
            >
              <h2
                class="
                  tracking-widest
                  text-xs
                  title-font
                  font-medium
                  text-black
                  mb-4
                  inline-block
                  py-1
                  px-2
                  rounded
                  bg-white
                "
              >
                VueJs | State | Vue.observable
              </h2>
              <h1
                class="title-font sm:text-3xl text-xl font-bold text-black mb-3"
              >
                Managing State With Vue.observable
              </h1>
              <p class="leading-relaxed mb-3 text-black">
                In this article, we’ll explain what Vue.observable is, and how
                we can use it to manage our simple store across our application
                in Vue.js.
              </p>
              <a class="text-black inline-flex items-center"
                >Read More
                <svg
                  class="w-4 h-4 ml-2"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                >
                  <path d="M5 12h14"></path>
                  <path d="M12 5l7 7-7 7"></path>
                </svg>
              </a>
              <div
                class="
                  text-center
                  mt-2
                  leading-none
                  flex
                  justify-center
                  absolute
                  bottom-0
                  left-0
                  w-full
                  py-4
                "
              ></div>
            </div>
          </div>

          <div class="p-4 lg:w-1/3">
            <div
              class="
                h-5/6
                px-8
                pt-14
                pb-24
                rounded-sm
                overflow-hidden
                relative
                article-card
              "
            >
              <h2
                class="
                  tracking-widest
                  text-xs
                  title-font
                  font-medium
                  text-black
                  mb-4
                  inline-block
                  py-1
                  px-2
                  rounded
                  bg-white
                "
              >
                Javascipt | Programming
              </h2>
              <h1
                class="title-font sm:text-3xl text-xl font-bold text-black mb-3"
              >
                Programming - Imperative vs Declarative
              </h1>
              <p class="leading-relaxed mb-3 text-black">
                In this post, we’ll go over what imperative and declarative in
                programming are, and the differences between them, with a code
                example.
              </p>
              <a class="text-black inline-flex items-center"
                >Read More
                <svg
                  class="w-4 h-4 ml-2"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                >
                  <path d="M5 12h14"></path>
                  <path d="M12 5l7 7-7 7"></path>
                </svg>
              </a>
              <div
                class="
                  text-center
                  mt-2
                  leading-none
                  flex
                  justify-center
                  absolute
                  bottom-0
                  left-0
                  w-full
                  py-4
                "
              ></div>
            </div>
          </div>
        </div>

        <div class="flex flex-wrap -m-4">
          <div class="p-4 lg:w-1/3">
            <div
              class="
                h-5/6
                px-8
                pt-12
                pb-24
                rounded-sm
                overflow-hidden
                relative
                article-card
              "
            >
              <h2
                class="
                  tracking-widest
                  text-xs
                  title-font
                  font-medium
                  text-black
                  mb-4
                  inline-block
                  py-1
                  px-2
                  rounded
                  bg-white
                "
              >
                State | Javascipt
              </h2>
              <h1
                class="title-font sm:text-3xl text-xl font-bold text-black mb-3"
              >
                Managing your State Application in Javascript
              </h1>
              <p class="leading-relaxed mb-3 text-black">
                In this article, we are going to give an in-depth explanation of
                what state is and how to manage your state application in pure
                Javascript.
              </p>
              <a class="text-black inline-flex items-center">Read More </a>
              <div
                class="
                  text-center
                  mt-2
                  leading-none
                  flex
                  justify-center
                  absolute
                  bottom-0
                  left-0
                  w-full
                  py-4
                "
              ></div>
            </div>
          </div>
          <div class="p-4 lg:w-1/3">
            <div
              class="
                h-5/6
                px-8
                pt-12
                pb-24
                rounded-sm
                overflow-hidden
                relative
                article-card
              "
            >
              <h2
                class="
                  tracking-widest
                  text-xs
                  title-font
                  font-medium
                  text-black
                  mb-4
                  inline-block
                  py-1
                  px-2
                  rounded
                  bg-white
                "
              >
                Vue | Component | Keep-alive
              </h2>
              <h1
                class="title-font sm:text-3xl text-xl font-bold text-black mb-3"
              >
                Caching your Dynamic components with Vue Keep-Alive
              </h1>
              <p class="leading-relaxed mb-3 text-black">
                In this article, we’ll explain what Vue.observable is, and how
                we can use it to manage our simple store across our application
                in Vue.js.
              </p>
              <a class="text-black inline-flex items-center"
                >Read More
                <svg
                  class="w-4 h-4 ml-2"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                >
                  <path d="M5 12h14"></path>
                  <path d="M12 5l7 7-7 7"></path>
                </svg>
              </a>
              <div
                class="
                  text-center
                  mt-2
                  leading-none
                  flex
                  justify-center
                  absolute
                  bottom-0
                  left-0
                  w-full
                  py-4
                "
              ></div>
            </div>
          </div>

          <div class="p-4 lg:w-1/3">
            <div
              class="
                h-5/6
                px-8
                pt-16
                pb-24
                rounded-sm
                overflow-hidden
                relative
                article-card
              "
            >
              <h2
                class="
                  tracking-widest
                  text-xs
                  title-font
                  font-medium
                  text-black
                  mb-4
                  inline-block
                  py-1
                  px-2
                  rounded
                  bg-white
                "
              >
                VueJS
              </h2>
              <h1
                class="title-font sm:text-3xl text-xl font-bold text-black mb-3"
              >
                Best Practices for Writing Vue.js
              </h1>
              <p class="leading-relaxed mb-3 text-black">
                In this post, we’ll go over what imperative and declarative in
                programming are, and the differences between them, with a code
                example.
              </p>
              <a class="text-black inline-flex items-center"
                >Read More
                <svg
                  class="w-4 h-4 ml-2"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                >
                  <path d="M5 12h14"></path>
                  <path d="M12 5l7 7-7 7"></path>
                </svg>
              </a>
              <div
                class="
                  text-center
                  mt-2
                  leading-none
                  flex
                  justify-center
                  absolute
                  bottom-0
                  left-0
                  w-full
                  py-4
                "
              ></div>
            </div>
          </div>
        </div>
        <p class="text-black text-center py-12">
          Read More of My <NuxtLink to="/blog">Articles</NuxtLink>
        </p>
      </div>
    </section>
  </main>
</template>

<style scoped>
.hero-section {
  background-color: #D8C6B6;
  color: #170D0B;
}
.article-section {
  background-color: #D8C6B6;
}
.article-card {
  background-color: #DDD6D3;
}
</style>
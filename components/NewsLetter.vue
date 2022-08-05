<template>
  <div class="p-6 container md:w-2/3 xl:w-auto mx-auto flex flex-col">
    <div class="w-full xl:w-3/5  xl:py-28 mx-auto">
      <h1
        class="
          text-2xl
          md:text-4xl
          xl:text-5xl
          font-bold
          leading-10
          text-white
          dark:text-white
          mb-4
          text-center
          xl:text-left
          md:mt-0
          mt-4
        "
      >
        Top Articles on my Blog
      </h1>
      <p
        class="
          text-base
          leading-normal
          text-white
          dark:text-gray-200
          text-center
          xl:text-left
        "
      >
        Be the first to get access to information and latest article on my blog
      </p>
      <div class="flex items-stretch mt-12">
        <input
          class="
            bg-gray-100
            rounded-sm rounded-r-none
            dark:bg-gray-800
            text-base
            leading-none
            text-gray-800
            dark:text-white
            p-5
            w-4/5
            border border-transparent
            focus:outline-none focus:border-gray-500
          "
          type="email"
          placeholder="Your Email"
        />
        <button
          class="
            w-32
            rounded-l-none
            bg-btn bg-opacity-90 hover:bg-opacity-100
            rounded
            text-base
            font-medium
            leading-none
            text-white
            p-5
            uppercase
            focus:outline-none
            focus:ring-2
            focus:ring-offset-2
            focus:ring-indigo-700
          "
        >
          Subscribe
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>
<style>
.bg-btn{
    background-color: #15CA82E6;
}
</style>
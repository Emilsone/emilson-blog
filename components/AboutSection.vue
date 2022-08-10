<template>
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
          <h1 class="title-font sm:text-4xl text-3xl mb-4 font-bold text-white">
            About Me
          </h1>
          <p class="mb-8 leading-relaxed text-white">
            I'm currently a technical writer and software developer. Aside from
            building web tools and applications, I realized that I'd want to do
            more than build. I'd also want to share resources, teach online, and
            guide developers. I enjoy educating people and simplifying
            complicated issues for their easy understanding.
          </p>
          <div class="flex justify-center"></div>
        </div>
        <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
          <img
            class="object-cover object-center rounded"
            alt="about-image"
            src="../assets/img/image-cartoon.png"
          />
        </div>
      </div>
</template>
<script>
export default {
    
}
</script>
<style>

</style>
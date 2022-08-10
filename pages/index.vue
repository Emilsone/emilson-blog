<!-- ./pages/index.vue -->
<template>
  <main>
    <section class="hero-section">
      <header>
        <!-- <h1 class="font-black text-8xl">Emilson Technical Blog</h1> -->
      </header>
    </section>

    <section class="body-font about-section">
      <AboutSection />
    </section>

    <!-- ARTICLE SECTION -->
    <section class="text-gray-600 body-font overflow-hidden">
      <div class="container px-5 py-24 mx-auto">
        <div class="-my-8 divide-y-2 divide-gray-100">
          <div class="py-8 flex flex-wrap md:flex-nowrap">
            <div class="md:w-64 md:mb-0 mb-6 flex-shrink-0 flex flex-col">
              <span class="font-semibold title-font text-gray-700"
                >CATEGORY</span
              >
              <span class="mt-1 text-gray-500 text-sm">12 Jun 2019</span>
            </div>
            <div class="md:flex-grow">
              <h1 class="text-4xl font-extrabold text-gray-900 title-font mb-2">
                Understanding JavaScript currying
              </h1>
              <p class="leading-relaxed">
                Currying is a function that takes one argument at a time and
                returns a new function expecting the next argument. It is a
                transformation of functions that translates a function from
                callable as f(a, b, c) into callable as f(a)(b)(c). In this
                article, we’re going to explore what currying is in Javascript,
                why and where you should use currying, and how to implement it
                with code examples.
              </p>
              <a
                class="
                  text-white
                  bg-black
                  py-3
                  px-4
                  inline-flex
                  items-center
                  mt-4
                "
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
            </div>
          </div>
          <div class="py-8 flex flex-wrap md:flex-nowrap">
            <div class="md:w-64 md:mb-0 mb-6 flex-shrink-0 flex flex-col">
              <span class="font-semibold title-font text-gray-700"
                >CATEGORY</span
              >
              <span class="mt-1 text-gray-500 text-sm">12 Jun 2019</span>
            </div>
            <div class="md:flex-grow">
              <h1 class="text-4xl font-extrabold text-gray-900 title-font mb-2">
                Programming - Imperative vs Declarative
              </h1>
              <p class="leading-relaxed">
                I have had a lot of questions from programmers regarding the
                differences between Declarative and Imperative programming, and
                most developers are unsure when to use which. In this post,
                we’ll go over what imperative and declarative in programming
                are, and the differences between them, with a code example
              </p>
              <a
                class="
                  text-white
                  bg-black
                  py-3
                  px-4
                  inline-flex
                  items-center
                  mt-4
                "
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
            </div>
          </div>
          <div class="py-8 flex flex-wrap md:flex-nowrap">
            <div class="md:w-64 md:mb-0 mb-6 flex-shrink-0 flex flex-col">
              <span class="font-semibold title-font text-gray-700"
                >CATEGORY</span
              >
              <span class="text-sm text-gray-500">12 Jun 2019</span>
            </div>
            <div class="md:flex-grow">
              <h1 class="text-4xl font-extrabold text-gray-900 title-font mb-2">
                Managing State With Vue.observable
              </h1>
              <p class="leading-relaxed">
                There are also other methods aside from Vue.observable, like
                Vuex and Pinia, that provide a similar solution to manage state;
                however, Vue.observable is preferable, as it is less complex and
                less verbose. In this article, we’ll explain what Vue.observable
                is, and how we can use it to manage our simple store across our
                application in Vue.js.
              </p>
              <a
                class="
                  text-white
                  bg-black
                  py-3
                  px-4
                  inline-flex
                  items-center
                  mt-4
                "
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
            </div>
          </div>
          <div class="py-8 flex flex-wrap md:flex-nowrap">
            <div class="md:w-64 md:mb-0 mb-6 flex-shrink-0 flex flex-col">
              <span class="font-semibold title-font text-gray-700"
                >CATEGORY</span
              >
              <span class="text-sm text-gray-500">12 Jun 2019</span>
            </div>
            <div class="md:flex-grow">
              <h1 class="text-4xl font-extrabold text-gray-900 title-font mb-2">
                Validating Forms with Vue Formulate
              </h1>
              <p class="leading-relaxed">
                When developing an application, we include a form. On the other
                hand, the management and validation of our form can be complex
                and repetitive. In this article, we’ll cover one of the Vue.js
                validation libraries (Vue Formulate), its capabilities, and how
                it validates our application. Vue.js’s setup and installation
                will not be covered in this tutorial, so you should already be
                familiar with those topics.
              </p>
              <a
                class="
                  text-white
                  bg-black
                  py-3
                  px-4
                  inline-flex
                  items-center
                  mt-4
                "
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
            </div>
          </div>
         


        </div>
         <div class="flex justify-center my-16">
            <a
              class="
                text-white
                bg-black
                py-3
                px-4
                inline-flex
                items-center
                mt-4
                
              "
              >Read More Articles
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
          </div>
      </div>
    </section>
    <!-- END OF ARTICLE SECTION -->

    <section class="text-white body-font news-section">
      <NewsLetter />
    </section>
    <section class="text-white body-font news-section">
      <FooterSection />
    </section>
  </main>
</template>
<script>
import AboutSection from "~~/components/AboutSection.vue";
import NewsLetter from "~~/components/NewsLetter.vue";
import FooterSection from "~~/components/FooterSection.vue";
export default {
  name: "About Section",
  components: {
    AboutSection,
    NewsLetter,
    FooterSection,
  },
};
</script>

<style scoped>
.hero-section {
  /* background-color: #ffff; */
  background-image: url(../assets/img/hero.png);
  /* color: #170d0b; */
  background-size: cover;
  height: 120vh;
}
.article-section {
  /* background-color: #15181e; */
}

.about-section {
  background-color: #010100;
}
.news-section {
  background-color: #010100;
}
</style>
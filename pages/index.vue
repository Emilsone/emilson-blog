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
              <h2 class="text-2xl font-medium text-gray-900 title-font mb-2">
                Bitters hashtag waistcoat fashion axe chia unicorn
              </h2>
              <p class="leading-relaxed">
                Glossier echo park pug, church-key sartorial biodiesel
                vexillologist pop-up snackwave ramps cornhole. Marfa 3 wolf moon
                party messenger bag selfies, poke vaporware kombucha
                lumbersexual pork belly polaroid hoodie portland craft beer.
              </p>
              <a class="text-indigo-500 inline-flex items-center mt-4"
                >Learn More
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
              <h2 class="text-2xl font-medium text-gray-900 title-font mb-2">
                Meditation bushwick direct trade taxidermy shaman
              </h2>
              <p class="leading-relaxed">
                Glossier echo park pug, church-key sartorial biodiesel
                vexillologist pop-up snackwave ramps cornhole. Marfa 3 wolf moon
                party messenger bag selfies, poke vaporware kombucha
                lumbersexual pork belly polaroid hoodie portland craft beer.
              </p>
              <a class="text-indigo-500 inline-flex items-center mt-4"
                >Learn More
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
              <h2 class="text-2xl font-medium text-gray-900 title-font mb-2">
                Woke master cleanse drinking vinegar salvia
              </h2>
              <p class="leading-relaxed">
                Glossier echo park pug, church-key sartorial biodiesel
                vexillologist pop-up snackwave ramps cornhole. Marfa 3 wolf moon
                party messenger bag selfies, poke vaporware kombucha
                lumbersexual pork belly polaroid hoodie portland craft beer.
              </p>
              <a class="text-indigo-500 inline-flex items-center mt-4"
                >Learn More
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
      </div>
    </section>
    <!-- END OF ARTICLE SECTION -->

     <section class="text-white body-font news-section">
      <NewsLetter />
     </section>
  </main>
</template>
<script>
import AboutSection from "~~/components/AboutSection.vue";
import NewsLetter from "~~/components/NewsLetter.vue";
export default {
  name: "About Section",
  components: {
    AboutSection,
    NewsLetter
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
  background-color: #15181e;
}
.news-section {
  background-color: #15181e;
}
</style>
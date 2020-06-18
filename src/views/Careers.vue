<template>
  <div class="Careers w-full">
    <navbar />
    <section>
      <div class="grid grid-cols-2 bg-gray-100 w-full">
        <div class="pt-48 py-16 px-20 lg:col-span-1 md:col-span-2">
          <h1
            class="lg:text-5xl sm:text-4xl md:text-5xl font-semibold lg:w-10/12 md:12/12 tracking-wide"
          >
            Find a job that suits
            <span class="text-blue-900">your skills.</span>
          </h1>
          <h3
            class="font-regular text-gray-700 text-lg py-5 leading-regular tracking-wide"
          >
            With just a few clicks, you can land a suitable job for yourself,
            <span class="pr-3 bg-gray-300 rounded-md">seamlessly.</span>
          </h3>
          <button
            class="shadow-none  bg-transparent border-2 border-blue-900 text-blue-900 hover:border-blue-700 hover:text-blue-700 font-semibold text-base py-3 px-8 rounded-md shadow-lg transition transition-colors duration-300 focus:outline-none"
          >
            Get Started
          </button>
        </div>
        <div class="mt-20 mr-24 md: hidden lg:grid">
          <img
            id="hero-image"
            class="md:hidden sm:hidden lg:grid"
            src="@/assets/home-images/career-hero-picture.png"
          />
        </div>
      </div>
    </section>
    <div class="grid px-20 py-20 lg:grid-cols-2 md:grid-cols-1">
      <div>
        <h1 class="font-semibold text-blue-800 text-3xl mb-10">
          Browse all job openings
        </h1>
        <form method="get">
          <input
            type="text"
            id="searchbar"
            placeholder="Search Keyword"
            name="searchbar"
            class="shadow-md px-4 py-4 text-lg rounded-l-md w-9/12 outline-none bg-gray-200"
            style="height:3rem"
          />
          <span>
            <button
              for="searchbar"
              style="height:3rem"
              class="bg-blue-900 text-white hover:bg-blue-800 hover:text-white font-semibold text-base py-2 px-6 rounded-tr-md rounded-br-md shadow-lg transition transition-colors duration-300 focus:outline-none"
            >
              Find now
            </button>
          </span>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
import navbar from "@/components/navbar.vue";
export default {
  data() {
    return {};
  },
  name: "Careers",
  components: { navbar },
};
</script>

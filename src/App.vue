<template>
  <div id="app" class=" overflow-x-hidden">
    <router-view class="sm: hidden md:hidden lg:grid" />
    <div class="text-center px-5 py-32">
      <img src="./assets/home-images/no-view.svg" class="mx-auto w-2/4" />
      <h1
        class="lg:hidden md:grid sm:grid mt-2 font-semibold text-2xl text-blue-900"
      >
        Oops!
        <p>Recommended for Large Screens</p>
      </h1>
      <p class="lg:hidden md:grid sm:grid text-gray-600">
        Responsive optimization still in progress
      </p>
    </div>
  </div>
</template>

<script>
export default {
  data() {},
};
</script>

<style>
body {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}
html {
  scroll-behavior: smooth;
}
</style>

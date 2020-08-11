<template>
  <div id="app" class=" overflow-x-hidden">
	<link href="https://fonts.googleapis.com/css2?family=Raleway:wght@100;200;300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <router-view class="sm: hidden md:hidden lg:grid" />
    <div class="text-center px-5 sm:pt-40  md:py-0 lg:hidden md:grid sm:grid">
      <img
        src="./assets/home-images/no-view.svg"
        class="lg:hidden md:grid sm:grid mx-auto w-2/4 mt-20"
      />
      <h1
        class="lg:hidden md:grid sm:grid mt-2 mb-4  font-semibold sm:text-2xl md:text-4xl text-blue-900"
      >
        <h1 class="font-bold">Oops!</h1>
        <p>Recommended for Large Screens</p>
      </h1>
      <p
        class="lg:hidden md:grid sm:grid text-gray-600 sm:text-base font-light md:text-lg tracking-wider"
      >
        Responsive optimization still in progress...
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
  font-family: "Raleway";
}
html {
  scroll-behavior: smooth;
}
</style>

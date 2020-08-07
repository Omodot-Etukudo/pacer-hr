<template>
  <header
    class="flex bg-white w-full h-20 px-5 py-3 flex justify-between shadow-md fixed"
  >
    <div class="flex flex-row">
      <div>
        <img
          class="h-10 ml-5 mr-10 my-2"
          src="@/assets/pacer-hrlogo.png"
          alt="Pacer-HR"
        />
      </div>
      <div class="flex">
        <ul class="font-semibold text-base font-sans">
          <a
            href="#hero"
            class="inline-block mx-10 my-4 hover:text-blue-700 transition transition-colors duration-300"
            >Home</a
          >
          <a
            href="#product"
            class="inline-block mx-10 my-4 hover:text-blue-700 transition transition-colors duration-300"
            >How It works</a
          >
          <a
            href="#other-benefits"
            class="inline-block mx-10 my-4 hover:text-blue-700 transition transition-colors duration-300"
            >About Us</a
          >
        </ul>
      </div>
    </div>
    <div class="flex flex-row items-start">
      <a
        class="px-3 py-2 mt-2 text-base font font-semibold font-sans hover:text-blue-700 transition transition-colors duration-300"
        href="#footer_item"
        >Contact Us</a
      >
      <button
        class="px-6 py-2 mt-2 mr-10 ml-5 bg-blue-900 text-white rounded-md hover:bg-blue-800 hover:shadow-md focus:outline-none font-semibold font-sans"
      >
        Sign In
      </button>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      navbuttons: [
        { index: "1", link: "Contact Us" },
        { index: "2", link: "Sign In", linkto: "signin" },
      ],
    };
  },
};
</script>

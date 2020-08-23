<template>
  <div id="app" class="bg-black text-white py-6 px-4 md:py-6 md:px-16">
    <BaseNavbar></BaseNavbar>
    <BaseSection></BaseSection>
    <BaseFooter></BaseFooter>
  </div>
</template>

<script>
import BaseNavbar from "@/components/base/BaseNavbar.vue";
import BaseSection from "@/components/base/BaseSection.vue";
import BaseFooter from "@/components/base/BaseFooter.vue";

export default {
  name: "App",
  components: {
    BaseNavbar,
    BaseSection,
    BaseFooter,
  },
};
</script>

<style>
:root {
  --global-font-family: "Lora", "Helvetica Neue", -apple-system,
    BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
  --global-secundary-font-family: "Montserrat", "Helvetica Neue", -apple-system,
    BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
  --global-menu-font-family: "Crimson Pro", "Helvetica Neue", -apple-system,
    BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
  --global-font-size: 1rem;
  --font-weight-regular: 400;
  --font-weight-bold: 700;
}
html,
body {
  font-family: var(--global-font-family);
  font-size: 16px;
  font-weight: var(--font-weight-regular);
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  scroll-behavior: smooth;
  margin: 0 auto;
}

.lora {
  font-family: var(--global-font-family);
}

.crimson-pro {
  font-family: var(--global-menu-font-family);
}

.montserrat {
  font-family: var(--global-secundary-font-family);
}
</style>

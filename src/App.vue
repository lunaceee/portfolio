<template>
  <div id="app">
    <div class="lg:container lg:mx-auto min-h-screen">
      <Header />
      <Main />
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Main from "@/components/Main.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    Main,
    Footer
  }
};
</script>

<template>
  <div>
    <Navbar />
    <Footer class="footer" />
  </div>
</template>
<style scoped>
.footer {
  position: absolute;
  bottom: 0;
  width: 100%;
}
</style>
<script>
import Navbar from "@/components/Navbar.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "Home",

  components: {
    Navbar,
    Footer,
  },
};
</script>

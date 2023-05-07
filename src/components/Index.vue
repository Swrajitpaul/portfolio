<template>
  <div class="hello">
    <PageHeader></PageHeader>
    <AboutMe></AboutMe>
    <PageFooter></PageFooter>
  </div>
</template>

<script>
import AboutMe from "./AboutMe.vue";
import PageHeader from "./PageHeader.vue";
import PageFooter from "./PageFooter.vue";
export default {
  components: { AboutMe, PageHeader, PageFooter },
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<style scoped></style>

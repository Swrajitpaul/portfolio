<template>
  <div class="hello">
    <PageHeader></PageHeader>
    <h1>
      SWRAJIT PAUL<span hidden id ="letter" style="color:salmon">'S</span>
    </h1>
    <h2 id="headertwo">
      Welcome to
    </h2>
    <h3 id="headerthree">
      Website
    </h3>
    <PageFooter></PageFooter>
  </div>
</template>

<script>
import PageHeader from "./PageHeader.vue";
import PageFooter from "./PageFooter.vue";
export default {
  components: { PageHeader, PageFooter },
  name: "HomePage",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
@import '../styles/HomePage.scss'
</style>

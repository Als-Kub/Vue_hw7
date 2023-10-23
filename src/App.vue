import ProductDetails from './components/ProductDetails.vue';
<template>
  <MainPage />
  <BlogPage />
  <BlogDetailsPage />
  <ProjectComp />
  <ProjectDetails />
</template>

<script>
import MainPage from "./components/MainPage.vue";
import BlogPage from "./components/BlogPage.vue";
import BlogDetailsPage from "./components/BlogDetailsPage.vue";
import ProjectComp from "./components/ProjectComp.vue";
import ProjectDetails from "./components/ProjectDetails.vue";

export default {
  components: {
    MainPage,
    BlogPage,
    BlogDetailsPage,
    ProjectComp,
    ProjectDetails,
  },
};
</script>

<style lang="scss"></style>

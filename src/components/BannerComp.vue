<template>
  <div class="banner center-wide">
    <div class="banner__box" :class="style">
      <div v-if="show" class="banner__content">
        <h2 class="banner__title">{{ title }}</h2>
        <p class="banner__links">
          <a href="#" class="banner__link">Home</a>
          <a href="#" class="banner__link">Blog</a>
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: String,
    style: String,
    show: Boolean,
  },
};
</script>

<style scoped></style>

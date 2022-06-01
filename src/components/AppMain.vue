<template>
  <div>
  <AppBanner/>
  <AppCourses/>
  <AppTutoring/>
  <AppReviews/>
  <AppNumbers/>
  </div>
</template>

<script>
import AppBanner from './AppBanner.vue';
import AppCourses from './AppCourses.vue';
import AppTutoring from './AppTutoring.vue';
import AppReviews from './AppReviews.vue';
import AppNumbers from './AppNumbers.vue';
export default {
name:'AppMain',
components: {
  AppBanner,
  AppCourses,
  AppTutoring,
  AppReviews,
  AppNumbers,
}
}
</script>

<style lang="scss" scoped>

</style>
<template>
  <div>
  <AppBanner/>
  <AppCourses/>
  <AppTutoring/>
  <AppReviews/>
  <AppNumbers/>
  <AppBestBlogs/>
  <AppSubscribe/>
  </div>
</template>

<script>
import AppBanner from './AppBanner.vue';
import AppCourses from './AppCourses.vue';
import AppTutoring from './AppTutoring.vue';
import AppReviews from './AppReviews.vue';
import AppNumbers from './AppNumbers.vue';
import AppBestBlogs from './AppBestBlogs.vue';
import AppSubscribe from './AppSubscribe.vue';
export default {
name:'AppMain',
components: {
    AppBanner,
    AppCourses,
    AppTutoring,
    AppReviews,
    AppNumbers,
    AppBestBlogs,
    AppSubscribe,
}
}
</script>

<style lang="scss" scoped>

</style>
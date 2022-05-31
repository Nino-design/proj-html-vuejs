<template>
  <div>
  <AppBanner/>
  <AppCourses/>
  </div>
</template>

<script>
import AppBanner from './AppBanner.vue';
import AppCourses from './AppCourses.vue';
export default {
name:'AppMain',
components: {
  AppBanner,
  AppCourses,
}
}
</script>

<style lang="scss" scoped>

</style>
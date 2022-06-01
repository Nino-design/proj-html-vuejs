<template>
  <section class="numbers text-center">
    <div class="container">
      <div class="row">
        <div class="card col-3">
          <h4 class="pb-5">Successfully trained</h4>
          <span class="pb-5 fs-1 fw-bold color-green-1">1790</span>
          <p class="font-big-grey ">enrolled learners</p>
        </div>
        <div class="card col-3">
          <h4 class="pb-5">Proudly Received</h4>
          <span class="pb-5 fs-1 fw-bold color-green-1">19</span>
          <p class="font-big-grey ">countrywide awards</p>
        </div>
        <div class="card col-3">
          <h4 class="pb-5">Firmly Established</h4>
          <span class="pb-5 fs-1 fw-bold color-green-1">24</span>
          <p class="font-big-grey">local branches</p>
        </div>
         <div class="card col-3">
          <h4 class="pb-5">Getting Featured on</h4>
          <span class="pb-5 fs-1 fw-bold color-green-1">1090</span>
          <p class="font-big-grey">blog posts</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppNumber",
};
</script>

<style lang="scss" scoped>

.card{
    width: calc(100% / 4 - 5px);
    margin: 0 2.5px;
    padding: 8rem 1.5rem;
}
</style>
<template>
  <div class="start container text-center pt-5 pb-5 mt-5">
    <p class="fs-4 mb-0">
      Subscribe
      <span class="color-green-1 fs-4"> Newsletters</span>
    </p>
    <h5 class="grey">
      Enter your email adress to register to our newsletter subscription
      delivered on a regular basis
    </h5>
      <input class="font-small-grey mt-4" type="text" placeholder="Enter your email" />
      <button type="button" class="btn btn button-green">
        Get started now
      </button>
  </div>
</template>

<script>
export default {
  name: "AppSubscribe",
};
</script>

<style lang="scss" scoped>
.grey {
  font-size: 1rem;
  color: #9ea4a5;
}
input {
  background-color: #f3e8ef;
  border: none;
  width: 200px;
  padding: 1.2em 0.6em;
}
.start {
  background: url(../assets/Img/maxcoach-shape-01.png) left top 30% no-repeat,
    url(../assets/Img/maxcoach-shape-02.png) right bottom 15% no-repeat;
  background-size: 100px, 100px;
}
</style>
<template>
  <section class="banner container">
    <div
      class="
        inner-banner
        d-flex
        justify-content-center
        align-items-center
        row
        mt-5
      "
    >
      <div class="col-6">
        <h1 class="fs-2">Distant learning for further expansion</h1>
        <p class="fs-6 color-light">
          Learning is a life-long journey that in fact we never find <br />
          the terminate stop. Stop searching, enjoy the process.
        </p>
        <button type="button" class="btn btn-primary">
          <i class="fa-solid fa-download"></i> Download free guide
        </button>
        <div class="question color-light">
          <span>Have a question?</span>
          <span class="color-green-1"
            >Get Free Sample <i class="fa-solid fa-arrow-right-long"></i
          ></span>
        </div>
      </div>
      <div class="img-banner col-6">
        <img
          src="../assets/Img/about-me-profile-ohm4dxoearqbxny7q3bq1pzbdgofdx0tobbeqcvzd0.jpg"
          alt=""
        />
      </div>
      <div class="d-flex justify-content-around align-items-center mt-5">
      <div class="clients col-2">
        <img src="../assets/Img/client-logo-01.png" alt="" />
      </div>
      <div class="clients col-2">
        <img src="../assets/Img/client-logo-02.png" alt="" />
      </div>
      <div class="clients col-2">
        <img src="../assets/Img/client-logo-03.png" alt="" />
      </div>
      <div class="clients col-2">
        <img src="../assets/Img/client-logo-04.png" alt="" />
      </div>
      <div class="clients col-2">
        <img src="../assets/Img/client-logo-05.png" alt="" />
      </div>
      <div class="clients col-2">
        <img src="../assets/Img/client-logo-06.png" alt="" />
      </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppBanner",
};
</script>

<style lang="scss" scoped>
.img-banner {
  background: url(../assets/Img/maxcoach-shape-07.png) left bottom 30% no-repeat,
    url(../assets/Img/maxcoach-shape-07-100x100.png) left top 30% no-repeat,
    url(../assets/Img/maxcoach-shape-02.png) right top 20% no-repeat,
    url(../assets/Img/maxcoach-shape-07-150x150.png) right bottom 10% no-repeat;
  background-size: 90px, 90px, 80px, 90px;

  img {
    width: 400px;
    margin-left: 2em;
    border-radius: 100%;
  }
}
button {
  background-color: #25ab94;
  color: white;
}
.question {
  font-size: 0.7rem;

  i {
    margin-top: 1rem;
  }
}

.clients img{
  width: 45%;
  margin: 0 -1rem;
}
</style>
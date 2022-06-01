<template>
  <section class="reviews mb-5 pb-5">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <p class="font-big-grey color-light mt-5 text-center">
            great words about maxcoach
          </p>
          <h2 class="mb-5 text-center">
            Our <span class="color-green-1">top learners'</span>verbatim
          </h2>
        </div>
      </div>
    </div>
    <div class="container-fluid">
      <div class="row g-2">
        <div class="card-container col-4">
          <h5>It's a choise of quality for people with special needs</h5>
          <p class="font-small-grey">
            I'm very strict person so i do require everything to be organized
            and neat. Then,i'll be able to makethings right and shine. MaxCoach
            guys just got me.
          </p>
          <div class="img-container">
            <img src="../assets/Img/testimonial-avata-03.jpg" alt="" />
            <div class="img-overlay" src="" alt=""></div>
          </div>
          <div class="info">
            <p class="name font-big-grey">FLORENCE THAMES</p>
            <span class="font-small-grey">/ Freelancer</span>
          </div>
        </div>
        <div class="card-container col-4">
          <h5>It's a choise of quality for people with special needs</h5>
          <p class="font-small-grey">
            I'm very strict person so i do require everything to be organized
            and neat. Then,i'll be able to makethings right and shine. MaxCoach
            guys just got me.
          </p>
          <div class="img-container">
            <img src="../assets/Img/testimonial-avata-02.jpg" alt="" />
          </div>
          <div class="info">
            <p class="name">MINA HOLLANCE</p>
            <span class="font-small-grey">/ Freelancer</span>
          </div>
        </div>
        <div class="card-container col-4">
          <h5>It's a choise of quality for people with special needs</h5>
          <p class="font-small-grey">
            I'm very strict person so i do require everything to be organized
            and neat. Then,i'll be able to makethings right and shine. MaxCoach
            guys just got me.
          </p>
          <div class="img-container">
            <img src="../assets/Img/testimonial-avata-01.jpg" alt="" />
            <div class="img-overlay" src="" alt=""></div>
          </div>
          <div class="info">
            <p class="name font-big-grey">MADLEY PONDOR</p>
            <span class="font-small-grey m-0 p-0">/ It specialist </span>
          </div>
        </div>
      </div>
    </div>
    <div class="dots container text-center mt-5">
      <i class="fa-solid fa-circle"></i>
      <i class="fa-solid fa-circle small"></i>
      <i class="fa-solid fa-circle small"></i>
      <i class="fa-solid fa-circle small"></i>
    </div>
    <div class="start container text-center pt-5 pb-5 mt-5 mb-5">
      <p class="fs-4 mb-0">
        Start today for getting
        <span class="color-green-1 fs-4"> Online Certification</span>
      </p>
      <h2>You can be your own guiding star with help!</h2>
      <button type="button" class="btn btn button-green mt-3">
        Get started now
      </button>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppReviews",
};
</script>

<style lang="scss" scoped>
section {
  background-color: #f6f3f5;
}

.card-container {
  width: calc(100% / 3 - 10px);
  margin-left: 0.5em;
  position: relative;
  padding: 2em;
  background: white;

  img {
    width: 20%;
    border-radius: 50%;
  }

  .img-overlay {
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
    background-color: rgba(246, 243, 245, 0.6);
  }

  .name {
    font-size: 0.7rem;
    font-weight: bold;
  }
}

.info {
  position: absolute;
  left: 120px;
  top: 160px;
}

.dots{
    i{
      padding: 2em;
    }

    .small{
        font-size: 0.7rem;
        color: #9ea4a5;
    }
}

.start{
    background: url(../assets/Img/maxcoach-shape-01.png) left top 30% no-repeat,
    url(../assets/Img/maxcoach-shape-02.png) right bottom 5% no-repeat;
  background-size: 100px, 100px;
}
</style>
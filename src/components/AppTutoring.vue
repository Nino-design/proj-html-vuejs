<template>
  <section class="tutoring mt-5 mb-5">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <p class="font-big-grey color-light mt-5 text-center">
            MAXCOACH AVAILABLE COURSES
          </p>
          <h2 class="mb-5 text-center">
            Access <span class="color-green-1">Smart Tutoring</span> Program For
            Benefits.
          </h2>
        </div>
        <div class="programs col-4">
          <img src="../assets/Img/home-2-image-box-01.png" alt="" />
          <h5 class="mt-4 mb-3">Customize Preferences</h5>
          <p class="mt-4 mb-3 font-small-grey">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Delectus
            corporis provident vitae ullam autem explicabo dolores, commodi
            magni beatae esse libero repellat
          </p>
          <p class="font-small-grey fw-bold">
            Start here <i class="fa-solid fa-arrow-right-long"></i>
          </p>
        </div>
        <div class="programs col-4 text-left">
          <img src="../assets/Img/about-us-02-image-box-02.png" alt="" />
          <h5 class="mt-4 mb-3">Customize Preferences</h5>
          <p class="mt-4 mb-3 font-small-grey">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Delectus
            corporis provident vitae ullam autem explicabo dolores, commodi
            magni beatae
          </p>
          <p class="font-small-grey fw-bold">
            Start here <i class="fa-solid fa-arrow-right-long"></i>
          </p>
        </div>
        <div class="programs col-4">
          <img src="../assets/Img/home-2-image-box-03.png" alt="" />
          <h5 class="mt-4 mb-3">Customize Preferences</h5>
          <p class="mt-4 mb-3 font-small-grey">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Delectus
            corporis provident vitae ullam autem explicabo dolores, commodi
          </p>
          <p class="font-small-grey fw-bold">
            Start here <i class="fa-solid fa-arrow-right-long"></i>
          </p>
        </div>
        <div class="img-wrapper pb-5 pt-5 col-7">
          <img src="../assets/Img/home-2-popup-video-poster.jpg" alt="" />
          <img class="img-icon" src="../assets/Img/icon-youtube-play.png" alt="">
        </div>
        <div class="mentoring col-5 d-flex flex-column justify-content-center">
        <p class="font-big-grey color-light text-left">
          get started <span class="black">effortlessly</span>
        </p>
        <h2 class=" text-left fs-1">
          Enjoy your <span class="color-green-1">Companionship</span>
        </h2>
        <p class="grey mb-5">Sneek peek what has in dtore for you on our online teaching and mentoring portal.Seek for some hidden hints of early-bind rewards as well.</p>
        <p class="color-green-1 fw-bold">Download free guidebook <i class="fa-solid fa-arrow-right-long"></i></p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppTutoring",
};
</script>

<style lang="scss" scoped>
.programs {
  margin-bottom: 8em;
}
.programs img {
  width: 40%;
  margin-top: 3em;
}
.img-wrapper {
  background: url(../assets/Img/maxcoach-shape-05-100x100.png) left top no-repeat,
    url(../assets/Img/maxcoach-shape-07-150x150.png) left top 30% no-repeat,
    url(../assets/Img/maxcoach-shape-07-150x150.png) right bottom -20% no-repeat;
  background-size: 120px, 120px, 160px;
  position: relative;

  .img-icon{
    position: absolute;
    width: 13%;
     top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
}
.img-wrapper img {
  width: 90%;
}
.black{ 
  color: black;
}

.grey{ 
  color: #9ea4a5;
  font-size: 1rem;
}
</style>
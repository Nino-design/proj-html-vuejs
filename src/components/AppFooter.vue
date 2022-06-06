<template>
  <section class="footer">
    <div class="footer-top mt-5 pt-5 mb-5">
      <div class="container">
        <div class="row">
          <div class="col-4">
            <h6>Adress</h6>
            <p class="font-small-grey">
              382 NE 191st St # 87394 Miami, FL 33179-3899
            </p>
            <p class="font-small-grey">
              +1(305) 547-9909(9am - 5pm EST, Monday-Friday)
            </p>
            <p class="font-small-grey">support@maxcoach.com</p>
            <div class="icons-container">
              <i class="fa-brands fa-facebook-square"></i>
              <i class="fa-brands fa-twitter"></i>
              <i class="fa-brands fa-instagram"></i>
              <i class="fa-brands fa-linkedin"></i>
            </div>
          </div>
          <div class="col-4">
            <div class="column d-flex flex-column justify-content-evenly">
              <h6 class="title">Explore</h6>
              <ul>
                <li
                  class="font-small-grey"
                  v-for="(element, index) in icons1"
                  :key="index"
                >
                  {{ element.text }}
                </li>
              </ul>
            </div>
          </div>
          <div class="col-4 ms-0 ps-0">
            <div class="column d-flex flex-column justify-content-evenly">
              <h6 class="title">Information</h6>
              <ul>
                <li
                  class="font-small-grey"
                  v-for="(element, index) in icons2"
                  :key="index"
                >
                  {{ element.text }}
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="footer-bottom container-fluid">
    <div class="container">
    <div class="row">
    <div class="col-6 d-flex justify-content-end align-items-center">
        <h6 class="font-small-grey">
          <i class="fa-solid fa-copyright pe-2"></i>MaxCoach. All Rights
          Reserved.
        </h6>
    </div>
    <div class="col-6 d-flex justify-content-end align-items-center">
        <div class="arrow">
        <span><i class="fa-solid fa-arrow-up-long"></i></span>
        </div>
      </div>
    </div>
    </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppFooter",
  props: {
    icons1: Array,
    icons2: Array,
  },
};
</script>

<style lang="scss" scoped>
.footer {
  background-color: #f6f3f5;
  width: 100%;

  .title{
    margin-left: 2em;
  }
}
.icons-container i {
  padding-right: 0.7em;
  color: #9ea4a5;
}

.arrow{
  width: 50px;
  height: 50px;
  text-align: center;
  border: 1px solis black;
  background-color: #1fad96;
   border-radius: 50%;

   i{
     line-height: 50px;
     color: white;
   }
 }
</style>
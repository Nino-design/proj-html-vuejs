<template>
  <section class="footer-top mt-5">
    <div class="container">
      <div class="row">
        <div class="col-6">
          <h6>Adress</h6>
          <p>382 NE 191st St # 87394 Miami, FL 33179-3899</p>
          <p>+1(305) 547-9909(9am - 5pm EST, Monday-Friday)</p>
          <p>support@maxcoach.com</p>
          <div class="icons-container">
            <i class="fa-brands fa-facebook-square"></i>
            <i class="fa-brands fa-twitter"></i>
            <i class="fa-brands fa-instagram"></i>
            <i class="fa-brands fa-linkedin"></i>
          </div>
        </div>
        <div class="col-6">
          <div class="column">
            <h6>Explore</h6>
            <ul> 
              <li v-for="(element, index) in icons" :key="index"></li>
              {{
                element.text
              }}
            </ul>
            <h6>Information</h6>
            <ul>
              <li v-for="(element, index) in icons2" :key="index"></li>
              {{
                element.text
              }}
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppFooter",
  data: function () {
    return {
       icons: [
        {
          text: "Start here",
        },
        {
          text: "Blog",
        },
        {
          text: "About us",
        },
        {
          text: "Success story",
        },
        {
          text: "Courses",
        },
        {
          text: "Contact us",
        },
      ],
      icons2: [
        {
          text: "Merbership",
        },
        {
          text: "Purchase guide",
        },
         {
          text: "Privacy policy",
        },
         {
          text: "Terms of services",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
</style>
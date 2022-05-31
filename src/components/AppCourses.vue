<template>
  <section class="courses mt-5 mb-5 pb-5">
    <div class="container">
      <div class="row text-center">
        <div class="col-12">
          <p class="mt-5 font-big-grey">Stimulated to learn?</p>
          <h2 class="mb-5">Featured Online Courses</h2>
        </div>
        <div class="course-type col-6">
          <img src="../assets/Img/course-02-480x298.jpg" alt="" />
          <div class="course-details">
            <p class="color-green-1 fw-bold">$40.00</p>
            <p class="fw-bold">Learning to write as a professional writer</p>
            <span class="font-small-grey"><i class="fa-solid fa-file-lines"></i>20 Lessons</span>
            <span class="font-small-grey"><i class="fa-solid fa-user"></i>50 Students</span>
          </div>
        </div>
         <div class="course-type col-6">
          <img src="../assets/Img/mobile-bg.jpg" alt="" />
          <div class="course-details">
            <p class="color-green-1 fw-bold">Free</p>
            <p class="fw-bold">Customer-centric-Info-Tech Strategies</p>
            <span class="font-small-grey"><i class="fa-solid fa-file-lines"></i>24 Lessons</span>
            <span class="font-small-grey"><i class="fa-solid fa-user"></i>769 Students</span>
          </div>
        </div>
         <div class="course-type col-6">
          <img src="../assets/Img/stock-full-hd-04-480x298.jpg" alt="" />
          <div class="course-details">
            <p class="color-green-1 fw-bold">$19.00</p>
            <p class="fw-bold">Open Programming Courses for Everyone: Python</p>
            <span class="font-small-grey"><i class="fa-solid fa-file-lines"></i>17 Lessons</span>
            <span class="font-small-grey"><i class="fa-solid fa-user"></i>62 Students</span>
          </div>
        </div>
         <div class="course-type col-6">
          <img src="../assets/Img/stock-full-hd-06-480x298.jpg" alt="" />
          <div class="course-details">
            <p class="color-green-1 fw-bold">$26.00</p>
            <p class="fw-bold">Academic Listening and Note-taking</p>
            <span class="font-small-grey"><i class="fa-solid fa-file-lines"></i>14 Lessons</span>
            <span class="font-small-grey"><i class="fa-solid fa-user"></i>67 Students</span>
          </div>
        </div>
         <div class="course-type col-6">
          <img src="../assets/Img/course-featured-image-01-480x298.jpg" alt="" />
          <div class="course-details">
            <p class="color-green-1 fw-bold">$39.00</p>
            <p class="fw-bold">Master jQuery in a Short Period Time</p>
            <span class="font-small-grey"><i class="fa-solid fa-file-lines"></i>6 Lessons</span>
            <span class="font-small-grey"><i class="fa-solid fa-user"></i>51 Students</span>
          </div>
        </div>
         <div class="course-type col-6">
          <img src="../assets/Img/stock-full-hd-05-480x298.jpg" alt="" />
          <div class="course-details">
            <p class="color-green-1 fw-bold">$59.00</p>
            <p class="fw-bold">Introduction to Javascript for Beginners</p>
            <span class="font-small-grey"><i class="fa-solid fa-file-lines"></i>14 Lessons</span>
            <span class="font-small-grey"><i class="fa-solid fa-user"></i>76 Students</span>
          </div>
        </div>
         <div class="col-12">
          <button type="button" class="btn btn button-green mt-3">View all courses <i class="fa-solid fa-arrow-right-long"></i></button>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppCourses",
};
</script>

<style lang="scss" scopes>
.courses {
  background-color: #f6f3f5;

  .course-type {
    display: flex;
    align-items: center;
    position: relative;
    margin: 2rem 0;

    img {
      width: 10rem;
      height: 10rem;
      border-radius: 50%;
    }

    .course-details {
      position: absolute;
      text-align: start;
      left: 220px;
      top: 20px;

      i {
          margin:0 0.5rem;
      }
    }
  }
}
</style>
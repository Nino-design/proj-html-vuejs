<template>
  <section class="blogs mt-5 pt-5 pb-4">
    <div class="container">
      <div class="row">
        <div class="col-4">
          <p class="font-big-grey">enjoyable insight</p>
          <h4 class="mb-5">
            Most Viewed<span class="color-green-1">Best Blogs</span>
          </h4>
          <div>
            <i class="fa-solid fa-arrow-right-long"></i>
            <span class="font-small-black">
              Become a Better Blogger: Content Planning
            </span>
          </div>
          <div>
            <i class="fa-solid fa-arrow-right-long"></i>
            <span class="font-small-black">
              Promoting Your Online Business on Pinterest
            </span>
          </div>
          <div>
            <i class="fa-solid fa-arrow-right-long"></i>
            <span class="font-small-black">Gamification and Game-Based Learning</span>
          </div>
          <div>
            <i class="fa-solid fa-arrow-right-long"></i>
            <span class="font-small-black">
              Designing on Online Course from Expert's Perspective
            </span>
          </div>
          <div>
            <i class="fa-solid fa-arrow-right-long"></i>
            <span class="font-small-black">
              Why Online Course Are the Future of Education
            </span>
          </div>
        </div>
        <div class="course-card col-4">
          <img src="../assets/Img/artist-blog-03-480x352.jpeg" alt="" />
          <p class="font-big-grey">artist</p>
          <p class="font-big-black fw-bold">
            Brush Strokes Energize Trees in Paintings
          </p>
          <span class="font-small-grey me-2">
            <i class="fa-solid fa-calendar"></i>May, 15 2020
          </span>
          <span class="font-small-grey"><i class="fa-solid fa-eye"></i>688 views</span>
        </div>
        <div class="course-card col-4">
          <img src="../assets/Img/artist-blog-01-480x352.jpg" alt="" />
          <p class="font-big-grey">artist</p>
          <p class="font-big-black fw-bold">
            Pocket Sized Notebooks Hold Miniature Paintings
          </p>
          <span class="font-small-grey me-2">
            <i class="fa-solid fa-calendar font-small-grey"></i>May, 15 2020
          </span>
          <span class="font-small-grey"><i class="fa-solid fa-eye"></i>603 views</span>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AppBestBlogs",
};
</script>

<style lang="scss" scoped>
.blogs{
    background-color: #f6f3f5;
}
.course-card{
    background-color: white;
    width: calc(100% / 3 - 60px);
    margin: 0 30px;
    padding: 0;

    p,span{
      margin: 1rem 2rem;
    }
    img{
        width: 100%;
    }
}
</style>
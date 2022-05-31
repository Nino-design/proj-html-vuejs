<template>
  <header>
      <div class="container d-flex justify-content-between align-items-center">
          <img class="logo" src="../assets/Img/dark-logo.png" alt="">
          <nav class="d-flex align-items-center">
              <ul class="d-flex align-items-center justify-content-around flex-grow-1">
                  <li v-for="(element, index) in headerList" :key="index"><span>{{ element.text }}</span><i :class="element.icon"></i></li>
              </ul>
              <div class="search d-flex align-items-center">
                  <a href=""><i class="user fa-solid fa-circle-user"></i></a>
                  <input type="text" placeholder="searh...">
                  <i class="lens fa-solid fa-magnifying-glass"></i>
              </div>
          </nav>
      </div>
  </header>
</template>

<script>
export default {
name:'AppHeader',

data() {
    return {
        headerList: [
            {
                text:"Home",
                icon:"fa-solid fa-angle-down",
            },
            {
                text:"Pages",
                icon:"fa-solid fa-angle-down",
            },
            {
                text:"Courses",
                icon:"fa-solid fa-angle-down",
            },
            {
                text:"Features",
                icon:"fa-solid fa-angle-down",
            },
            {
                text:"Blog",
                icon:"fa-solid fa-angle-down",
            },
            {
                text:"Shop",
                icon:"fa-solid fa-angle-down",
            },
        ],
    };
},

};
</script>

<style lang="scss" scoped>

header {
    box-shadow:0px 2px 2px rgb(233, 228, 228);
}
.logo{ 
    width: 10%;
}
ul{ 
    margin-right: 3em;
    margin-top: 1em;
    li{ 
        padding: 0.7em;
        margin-right: 0.3em;
        font-size: 0.8em;
    }
    i{ 
        margin-left: 0.7em;
    }
}

.user{ 
    color: black;
    margin-right: 0.5em;
}

.lens{ 
    color: #1fad96;
}


</style>
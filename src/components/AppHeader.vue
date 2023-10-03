<script>
export default {
    name: 'AppHeader'
}


</script>

<template>
  <header id="app_header">
     <div class="top d-flex justify-content-around py-2">
        <div>
            <img class="p-1" src="../../src/assets/img/image (email).svg"  alt="">
            <span>Superhit Top Movie <strong class="px-1">**King Star**</strong></span>
            <img class="p-1" src="../../src/assets/img/image (f).svg"  alt="">
            <img class="p-1" src="../../src/assets/img/image (t).svg"  alt="">
            <img class="p-1" src="../../src/assets/img/image (in).svg"  alt="">
            <img class="p-1" src="../../src/assets/img/image (inst).svg"  alt="">
            <img class="p-1" src="../../src/assets/img/image (g+).svg"  alt="">
        </div>
        <div>
            <img class="p-1" src="../../src/assets/img/image (lock).svg"  alt="">
            <span>Login</span>
        </div>
     </div>
     <!-- End Top -->
     <div class="search d-flex justify-content-around border border-black border-start-0 border-end-0">
        <div class="p-2">
          <img src="../../src/assets/img/cropped-logo.png" alt="">
        </div>
        <div class="d-flex my-3 py-3">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-success" type="submit">Search</button>
        </div>
     </div>
     <!-- End Search -->
     <div class="nav_bar"></div>
     <div class="jumbotron">
     </div>
  </header>
  
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

#app_header {
    .top {
        color: $Cinema_light;
    }

    strong {
        color: $Cinema_primary;
    }
}
</style>

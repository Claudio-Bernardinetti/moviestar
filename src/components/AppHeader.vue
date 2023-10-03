<script>
export default {
    name: 'AppHeader'
}


</script>

<template>
  <header id="app_header">
     <div class="top d-flex justify-content-space-around">
        <div>
            <img class="p-1" src="../../src/assets/img/image (email).svg"  alt="">
            <span>Superhit Top Movie <strong class="px-1 text-success">**King Star**</strong></span>
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
     <div class="search">
        <img src="../../src/assets/img/cropped-logo.png" alt="">
     </div>
     <div class="nav_bar"></div>
     <div class="jumbotron">
     </div>
  </header>
  
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.top {
    color: $Cinema_light;
    background-color: c;
}

</style>

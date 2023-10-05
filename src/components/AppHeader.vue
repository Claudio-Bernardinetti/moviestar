<script>
export default {
    name: 'AppHeader'
}


</script>

<template>
  <header id="app_header">
     <div class="top d-flex justify-content-around  py-2">
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
          <input class="search form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn" type="submit">Search</button>
        </div>
     </div>
     <!-- End Search -->
     <div class="nav_bar">
        <nav class="navbar navbar-expand-lg text-color">
          <div class="container-fluid">
            
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item ">
                    
                  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="true">Home</a>
                  <ul class="dropdown-menu bg-black">
                    <li><a class="dropdown-item" href="#">Home 1</a></li>
                    <li><a class="dropdown-item" href="#">Home 2</a></li>
                    <li><a class="dropdown-item" href="#">Home 3</a></li>
                    <li><a class="dropdown-item" href="#">Home 4</a></li>
                    <li><a class="dropdown-item" href="#">Home 5</a></li>
                    <li><a class="dropdown-item" href="#">Home 6</a></li>
                  </ul>
                </li>
                <li class="nav-item">
                  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="true">Celebrity</a>
                </li>
                <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="true">
                   Movie
                  </a>
                  
                </li>
                <li class="nav-item">
                  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="true">Page</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="true">Shop</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Blog</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Contact Us</a>
                </li>
              </ul>
              <div class="basket">
                    <span class="position-absolute top-10 start-100 translate-middle badge rounded-pill">
                    0
                    </span>
                 <img src="../../src/assets/img/image (basket).svg"  alt="">
              </div>
            </div>
        </div>
    </nav>
    <!-- End Navbar -->
     </div>
     <div class="jumbotron">
        <div class="text">
            <h6>Welcome To Our Movie Site</h6>
            <h2>OUR SPECIAL <span>MOVIES</span></h2>
            <p class="text-center">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Suscipit cupiditate sequi voluptate aliquam dolor, placeat architecto accusamus, minima maiores quidem expedita. Impedit natus aperiam asperiores dolores at eaque.</p>
            <button>Read More</button>
        </div>
     </div>
     <!-- End Jumbotron -->
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

    .btn {
        background-color: $Cinema_primary;
    }
    a {
        color: $Cinema_light;
    }
    .nav_bar {
        padding-left: 16%;
        padding-right: 18%;
        .basket{
            span{
                background-color: $Cinema_primary;
            }
        }
    }
    .jumbotron{
        background-image: url(../../src/assets/img/slider-1536x520.jpg);
        width: 100%;
        height: 520px;
        .text {
            display: flex;
            flex-direction: column;
            align-items: center;
            color: $Cinema_light;
            padding-top: 6rem;
            padding-left: 40%;
            padding-right: 30%;
            span {
                color: $Cinema_primary;
            }
            button {
                background-color: $Cinema_primary;
                border-radius: 15px;
                 &:hover {
                background-color: $Cinema_light;
            }
            }
        }
    }
}
</style>

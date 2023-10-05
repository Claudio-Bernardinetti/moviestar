<script>
export default {
    name: 'AppFooter'
}


</script>

<template>
  <footer id="app_footer">
      <div class="footer_top">
        <div class="lists d-flex">
          <div class="about col-3 p-3">
            <h5>About Us</h5>
            <div class="line"></div>
              <p class="py-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo laborum iure temporibus repellat id ipsum, deleniti debitis cum quis velit dolorum ipsam iusto magnam quo quisquam!</p>
              <div class="icons d-flex">
                <div class="facebook rounded-circle">
                  <img src="../../src/assets/img/image (f-w).svg" alt="">
                </div>
                <div class="twitter rounded-circle">
                  <img src="../../src/assets/img/image (t-w).svg" alt="">
                </div>
                <div class="linkedin rounded-circle">
                  <img src="../../src/assets/img/image (in-w).svg" alt="">
                </div>
                <div class="instagram rounded-circle">
                  <img src="../../src/assets/img/image (inst-w).svg" alt="">
                </div>
                <div class="pinterest rounded-circle">
                  <img src="../../src/assets/img/image (p-w).svg" alt="">
                </div>
              </div>
          </div>
          <!-- End About list -->
          <div class="movie col-2 p-3">
            <h5>Movie Category</h5>
            <div class="line"></div>
            <p class="pt-4">English New Movie</p>
            <p>Hindi All Movie</p>
            <p>Latest Tamil Movie</p>
            <p>New Top Rating Movie</p>
            <p>Hornn New Movie</p>
            <p>Animation New Movie</p>
          </div>
          <!-- End Movie list -->
          <div class="information col-2 p-3">
            <h5>Information</h5>
            <div class="line"></div>
            <p class="pt-4">Youtube Video Post</p>
            <p>Actor Information</p>
            <p>New Promotion</p>
            <p>Latest Movie In English</p>
            <p>Latest Film Product</p>
            <p>Video New Video</p>
          </div>
          <!-- End Information list -->
          <div class="recent col-3 p-3">
            <h5>Recent Posts</h5>
            <div class="posts">
              <div class="top mb-3 d-flex">
                <img src="../../src/assets/img/blog-100x100.jpg" alt="">
                <div>
                  <h6>Actor The Concept Movie High Concept Theotry see</h6>
                  <h6>April 14,2020</h6>
                </div>
              </div>
              <div class="midle mb-3 d-flex">
                <img src="../../src/assets/img/blog2-100x100.jpg" alt="">
                <div>
                  <h6>Actor The Concept Movie High Concept Theotry see</h6>
                  <h6>April 14,2020</h6>
                </div>
              </div>
              <div class="bottom d-flex">
                <img src="../../src/assets/img/blog3-100x100.jpg" alt="">
                <div>
                  <h6>Actor The Concept Movie High Concept Theotry see</h6>
                  <h6>April 14,2020</h6>
                </div>
              </div>
            </div>
          </div>
          <!-- End Recent list -->
        </div>
      </div>
      <!-- End Footer top -->
      <div class="footer_bottom">
        <div class="d-flex justify-content-around pt-3">
          <div class="left d-flex">
            <p>Term And Conditions</p>
            <p>Policy</p>
            <p>About</p>
          </div>
          <div class="right d-flex">
            <img src="" alt="">
            <p>&#169; 2020 <span>@Themepul</span> All Rights Reserved.</p>
          </div>
        </div>
      </div>
  </footer>
  
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

#app_footer {
    color: $Cinema_light_dark;
  .footer_top {
    background: linear-gradient(rgba(23, 32, 43, 0.9), rgba(23, 32, 43, 0.9)), url(../../src/assets/img/ft-bg.jpg);
    height: 500px;
    width: 100%;
    margin-top: -7em;
    .lists {
      color: $Cinema_light;
      margin-left: 15%;
      padding-top: 2rem;
      .icons {
        .facebook, .twitter, .linkedin, .instagram, .pinterest {
          width: 40px;
          height: 40px;
          padding-left: 14px;
          padding-right: 14px;
          padding-top: 5px;
          margin-right: 0.5rem;
          cursor: pointer; 
          &:hover {
            background-color: transparent;
            
          }
        }
        .facebook{
          background-color: $Cinema_facebook;
          padding-left: 16px;
          padding-right: 16px;
        }
        .twitter {
          background-color: $Cinema_twitter;
        }
        .linkedin {
          background-color: $Cinema_linkedin;
        }
        .instagram {
          background-color: $Cinema_instagram;
        }
        .pinterest {
          background-color: $Cinema_pinterest;
          padding-left: 12px;
          padding-right: 18px;
        }
      }
    }
    .line {
      border: 2px solid $Cinema_light;
      width: 40px;
    }
    .recent {
      img {
        margin-right: 0.5rem;
      }
    }
  }
  .footer_bottom {
    color: $Cinema_light;
    .left {
      p {
        padding-right: 2rem;
      }
    }
    .right {
      span {
        color: $Cinema_primary;
      }
    }
  }
}

</style>
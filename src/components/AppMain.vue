<script>
export default {
    name: 'AppMain'
}


</script>

<template>
  <div id="app_main">
    <div class="new_movie_container">
        <div class="new_movie d-flex border-bottom border-black">
            <div class="line"></div>
            <div class="text px-2">
                <h4>New Movie</h4>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi, hic doloremque!</p>
            </div>
        </div>
        <div class="photos d-flex justify-content-center align-items-center">
            <div class="left_pic d-flex flex-column justify-content-between">
              <div class="d-flex justify-content-end p-2"><span>&#9733; </span> 0/10</div>
              <div>
                <div class="p-2">
                    <h5>Hurry Animate Blue Strack New Movies</h5>
                    <h6>Category: Top Rating</h6>
                </div>
                <div class="d-flex justify-content-between py-3">
                    <div class="bg-black p-2 rounded-end-pill">Details</div>
                    <div class="bg-black p-2 rounded-start-pill">381 Views</div>
                </div>
              </div>
            </div>
            <!-- End left_pic -->
            <div class="midle_pic d-flex flex-column justify-content-between">
              <div class="d-flex justify-content-end p-2"><span>&#9733; </span> 4/10</div>
              <div>
                <div class="p-2">
                    <h5>Quisque Auctor Movie In Strack</h5>
                    <h6>Category: Coming Soon</h6>
                </div>
                <div class="d-flex justify-content-between py-3">
                    <div class="bg-black p-2 rounded-end-pill">Details</div>
                    <div class="bg-black p-2 rounded-start-pill">947 Views</div>
                </div>
              </div>
            </div>
            <!-- End midle_pic -->
            <div class="right_pic d-flex flex-column justify-content-between">
              <div class="d-flex justify-content-end p-2"><span>&#9733; </span> 0/10</div>
              <div>
                <div class="p-2">
                    <h5>New Movie Quisque in Strack</h5>
                    <h6>Category: Latest Movie</h6>
                </div>
                <div class="d-flex justify-content-between py-3">
                    <div class="bg-black p-2 rounded-end-pill">Details</div>
                    <div class="bg-black p-2 rounded-start-pill">721 Views</div>
                </div>
              </div>
            </div>
            <!-- End right_pic -->
        </div>
        <!-- End photos -->
    </div>
     <!-- End New Movie -->
     <div class="movie_playlist d-flex border-bottom border-black">
        <div class="line"></div>
        <div class="text px-2">
            <h4>Movie Playlist</h4>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi, hic doloremque!</p>
        </div>
     </div>
     <!-- End Movie Playlist -->
     <div class="coming_soon"></div>
     <!-- End Coming Soon -->
     <div class="new_movie_navbar d-flex border-bottom border-black">
        <div class="line"></div>
        <div class="text px-2">
            <h4>New Movie</h4>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi, hic doloremque!</p>
        </div>
     </div>
     <!-- End New Movie Navbar -->
     <div class="latest_news d-flex border-bottom border-black">
        <div class="line"></div>
        <div class="text px-2">
            <h4>Latest News</h4>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi, hic doloremque!</p>
        </div>
     </div>
     <!-- End Latest News -->
     <div class="subscribe"></div>
     <!-- End Subscribe -->
  </div>
  
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;
 #app_main{
    height: 1000px;
    .new_movie, .movie_playlist, .new_movie_navbar, .latest_news{
            margin-left: 16%;
            margin-right: 16%;
            margin-top: 4rem;
            margin-bottom: 4rem;
            padding-bottom: 0rem;
            
            
        .line{
            border: 3px solid $Cinema_primary;
           
        }
        .text{
            color: $Cinema_light;
            padding-top: 0.5rem;
        }
    }
    .new_movie_container{
        .photos{
            .left_pic, .right_pic {
                width: 300px;
                height: 400px;
                color: $Cinema_light;
                border-radius: 15px;
                filter: brightness(50%);
                span{
                    color: $Cinema_primary;
                }
            }
            .left_pic{
                background-image: url(../../src/assets/img/1.jpg);
            }
            .midle_pic{
                background-image: url(../../src/assets/img/2.jpg);
                width: 350px;
                height: 500px;
                color: $Cinema_light;
                border-radius: 15px;  
                span{
                    color: $Cinema_primary;
                } 
            }
            .right_pic{
               background-image: url(../../src/assets/img/5.jpg); 
            }
        }
    }
 }
</style>


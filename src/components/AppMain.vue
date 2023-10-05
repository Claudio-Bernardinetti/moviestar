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
     <div class="movie_playlist_container">
        <div class="movie_playlist d-flex border-bottom border-black">
            <div class="line"></div>
            <div class="text px-2">
                <h4>Movie Playlist</h4>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi, hic doloremque!</p>
            </div>
        </div>
        <div class="you_tube_container d-flex flex-wrap">
            <div class="you_tube col-5  justify-content-between">
                <iframe width="100%" height="100%" src="https://www.youtube.com/embed/BP0k4SdquG0?si=pAmDOU3qydbb31sT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                <!-- <div class="d-flex">
                    <img class="rounded-circle p-1" src="../../src/assets/img/channels4_profile.jpg" width="50px" height="50px" alt="">
                    <div>Yeh Saali Aashiqui | Official Trailer | Vardhan Puri, Shivaleek...</div>
                    <div>
                        <img src="../../src/assets/img/image (clock).svg" alt="">
                        <div>Guarda piu'...</div>
                    </div>
                    <div class="px-1">
                        <img src="../../src/assets/img/image (share).svg" alt="">
                        <div>Condividi</div>
                    </div>
                </div>
                <div class="d-flex  my-2 p-1 bg-gradient">
                    <div>Guida su </div>
                    <img class="p-1" src="../../src/assets/img/image (11).svg" width="5%" alt="">
                    <div>You Tube</div>
                </div> -->
            </div>
            <div class="new_movie mx-4">
                <div class="border-bottom border-black p-2">
                    <div>New Movie</div>
                    <div>Playng 24</div>
                </div>
                <div class="new_movie_overflow">
                    <div class="d-flex p-2">
                        <div>
                        <img src="../../src/assets/img/2-100x100.jpg" alt="">
                        </div>
                        <div class="px-2">
                            <h5>Quisque auctor Movie In Strack</h5>
                            <div>947 Views</div>
                            <div class="d-flex justify-content-between">
                                <div>February 12,2016</div>
                                <div>2.30.00</div>
                            </div>
                        </div>
                    </div>
                    <div class="d-flex p-2">
                        <div>
                        <img src="../../src/assets/img/3-100x100.jpg" alt="">
                        </div>
                        <div class="px-2">
                            <h5>Quisque auctor Movie In Strack</h5>
                            <div>947 Views</div>
                            <div class="d-flex justify-content-between">
                                <div>February 12,2016</div>
                                <div>2.30.00</div>
                            </div>
                        </div>
                    </div>
                    <div class="d-flex p-2">
                        <div>
                        <img src="../../src/assets/img/5-100x100.jpg" alt="">
                        </div>
                        <div class="px-2">
                            <h5>Quisque auctor Movie In Strack</h5>
                            <div>947 Views</div>
                            <div class="d-flex justify-content-between">
                                <div>February 12,2016</div>
                                <div>2.30.00</div>
                            </div>
                        </div>
                    </div>
                    <div class="d-flex p-2">
                        <div>
                        <img src="../../src/assets/img/6-100x100.jpg" alt="">
                        </div>
                        <div class="px-2">
                            <h5>Quisque auctor Movie In Strack</h5>
                            <div>947 Views</div>
                            <div class="d-flex justify-content-between">
                                <div>February 12,2016</div>
                                <div>2.30.00</div>
                            </div>
                        </div>
                    </div>
                </div>
                
            </div>
        </div>
    </div>
     <!-- End Movie Playlist -->
     <div class="coming_soon">
        <div class="text">
            <h6><span>COMING SOON MOVIE</span></h6>
            <h1>MAX STILL</h1>
            <div class="text_opacity text-center px-2">
               <h6>JON PLAYER<span> & </span>EMILY ROSE</h6> 
               <p>THE COUNTDOWN IS FINISHED!</p>
            </div>
        </div>
     </div>
     <!-- End Coming Soon -->
     <div class="new_movie_navbar_container">
        <div class="new_movie_navbar d-flex border-bottom border-black">
            <div class="line"></div>
            <div class="text px-2">
                <h4>New Movie</h4>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi, hic doloremque!</p>
            </div>
        </div>
        <div class="nav_bar d-flex">
            <div>All</div>
            <div>Coming soon</div>
            <div>Latest Movie</div>
            <div>Top Rating</div>
            <div>TV Series</div>
        </div>
        <!-- End Navbar -->
        <div class="img d-flex flex-wrap justify-content-center">
            <div class="hurry d-flex flex-column justify-content-between">
                <div class="d-flex justify-content-start position-relative">
                    <div class="hover_green col-4 mt-3 p-2 rounded-end-pill">20.30.00</div>
                    <div class="star mt-3 p-2"><span> &#9733; </span> 0/10</div> 
                </div>
                <div>
                    <div class="p-2">
                        <div class="hover d-flex justify-content-center mb-2">
                          <img class="hover"  src="../../src/assets/img/image (play).svg" width="20%" alt="">
                        </div>
                        <h5>Hurry Animate Blue Strack New Movie</h5>
                        <h6>Category: Top Rating</h6>
                        <h6 class="hover">Release: February 12, 2016</h6>
                        <h6 class="hover">Genres: Drama, Action Release</h6>
                    </div>
                    <div class="d-flex justify-content-between py-3">
                        <div class="bg-black p-2 rounded-end-pill">Details</div>
                        <div class="bg-black p-2 rounded-start-pill">381 Views</div>
                    </div>
                </div>
            </div>
            <!-- End Hurri pic -->
            <div class="animate d-flex flex-column justify-content-between">
                <div class="d-flex justify-content-start position-relative">
                    <div class="hover_green col-4 mt-3 p-2 rounded-end-pill">20.30.00</div>
                    <div class="star mt-3 p-2"><span> &#9733; </span> 0/10</div> 
                </div>
                <div>
                    <div class="p-2">
                        <div class="hover d-flex justify-content-center mb-2">
                          <img class="hover"  src="../../src/assets/img/image (play).svg" width="20%" alt="">
                        </div>
                        <h5>Animate Blue Strack New Movie</h5>
                        <h6>Category: Latest Movie</h6>
                        <h6 class="hover">Release: February 12, 2016</h6>
                        <h6 class="hover">Genres: Drama, Action Release</h6>
                    </div>
                    <div class="d-flex justify-content-between py-3">
                        <div class="bg-black p-2 rounded-end-pill">Details</div>
                        <div class="bg-black p-2 rounded-start-pill">343 Views</div>
                    </div>
                </div>
            </div>
            <!-- End Animat pic -->
            <div class="blue d-flex flex-column justify-content-between">
                <div class="d-flex justify-content-start position-relative">
                    <div class="hover_green col-4 mt-3 p-2 rounded-end-pill">20.30.00</div>
                    <div class="star mt-3 p-2"><span> &#9733; </span> 0/10</div> 
                </div>
                <div>
                    <div class="p-2">
                        <div class="hover d-flex justify-content-center mb-2">
                          <img class="hover"  src="../../src/assets/img/image (play).svg" width="20%" alt="">
                        </div>
                        <h5>Blue Strack New Animate Movie</h5>
                        <h6>Category: Coming Soon</h6>
                        <h6 class="hover">Release: February 12, 2016</h6>
                        <h6 class="hover">Genres: Drama, Action Release</h6>
                    </div>
                    <div class="d-flex justify-content-between py-3">
                        <div class="bg-black p-2 rounded-end-pill">Details</div>
                        <div class="bg-black p-2 rounded-start-pill">420 Views</div>
                    </div>
                </div>
            </div>
            <!-- End Blue pic -->
            <div class="nulla d-flex flex-column justify-content-between">
                <div class="d-flex justify-content-start position-relative">
                    <div class="hover_green col-4 mt-3 p-2 rounded-end-pill">20.30.00</div>
                    <div class="star mt-3 p-2"><span> &#9733; </span> 0/10</div> 
                </div>
                <div>
                    <div class="p-2">
                        <div class="hover d-flex justify-content-center mb-2">
                          <img class="hover"  src="../../src/assets/img/image (play).svg" width="20%" alt="">
                        </div>
                        <h5>Nulla Strack New Animate Movie</h5>
                        <h6>Category: TV Series</h6>
                        <h6 class="hover">Release: February 12, 2016</h6>
                        <h6 class="hover">Genres: Drama, Action Release</h6>
                    </div>
                    <div class="d-flex justify-content-between py-3">
                        <div class="bg-black p-2 rounded-end-pill">Details</div>
                        <div class="bg-black p-2 rounded-start-pill">324 Views</div>
                    </div>
                </div>
            </div>
            <!-- End Nulla pic -->
            <div class="quisque d-flex flex-column justify-content-between">
                <div class="d-flex justify-content-start position-relative">
                    <div class="hover_green col-4 mt-3 p-2 rounded-end-pill">20.30.00</div>
                    <div class="star mt-3 p-2"><span> &#9733; </span> 1/10</div> 
                </div>
                <div>
                    <div class="p-2">
                        <div class="hover d-flex justify-content-center mb-2">
                          <img class="hover"  src="../../src/assets/img/image (play).svg" width="20%" alt="">
                        </div>
                        <h5>Quisque In Strack New Movie</h5>
                        <h6>Category: Top Rating</h6>
                        <h6 class="hover">Release: February 12, 2016</h6>
                        <h6 class="hover">Genres: Drama, Action Release</h6>
                    </div>
                    <div class="d-flex justify-content-between py-3">
                        <div class="bg-black p-2 rounded-end-pill">Details</div>
                        <div class="bg-black p-2 rounded-start-pill">339 Views</div>
                    </div>
                </div>
            </div>
            <!-- End Quisque pic -->
            <div class="new d-flex flex-column justify-content-between">
                <div class="d-flex justify-content-start position-relative">
                    <div class="hover_green col-4 mt-3 p-2 rounded-end-pill">20.30.00</div>
                    <div class="star mt-3 p-2"><span> &#9733; </span> 0/10</div> 
                </div>
                <div>
                    <div class="p-2">
                        <div class="hover d-flex justify-content-center mb-2">
                          <img class="hover"  src="../../src/assets/img/image (play).svg" width="20%" alt="">
                        </div>
                        <h5>New Movie Quisque in Strack</h5>
                        <h6>Category: Latest Movie</h6>
                        <h6 class="hover">Release: February 12, 2016</h6>
                        <h6 class="hover">Genres: Drama, Action Release</h6>
                    </div>
                    <div class="d-flex justify-content-between py-3">
                        <div class="bg-black p-2 rounded-end-pill">Details</div>
                        <div class="bg-black p-2 rounded-start-pill">503 Views</div>
                    </div>
                </div>
            </div>
            <!-- End New pic -->
        </div>
     </div>
     <!-- End New Movie Navbar -->
     <div class="latest_news_container">
        <div class="latest_news d-flex border-bottom border-black">
            <div class="line"></div>
            <div class="text px-2">
                <h4>Latest News</h4>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Sequi, hic doloremque!</p>
            </div>
        </div>
        <!-- Start images -->
        <div class="last_news_img_container container">
            <div class="row">
                <div class="actor p-0 d-flex col-12 col-lg-6  flex-column justify-content-between">
                    <div class="d-flex justify-content-end "></div>
                    <div>
                        <div class="p-2">
                            <h5>Actor The Concept Movie High Concept Theory See The Post</h5>
                        </div>
                        <div class="d-flex justify-content-between py-3">
                            <div class="bg-black p-2 rounded-end-pill">Details</div>
                            <div class=" p-2 rounded-start-pill">moviestar 0 Comments Share</div>
                        </div>
                    </div>
                </div>
                <!-- End Actor img -->
                <div class="four_squares col-12 col-lg-6 ">
                    <div class="row justify-content-center">
                        <div class="consequat p-0 d-flex col-12 col-md-6 col-lg-6 flex-column  justify-content-between">
                            <div class="d-flex justify-content-end "></div>
                            <div>
                                
                                <div class="p-2">
                                    <h5>Consequat Nam Lectus Nibh Aucibus It Has Turpis</h5>
                                </div>
                                <div class="d-flex justify-content-between py-3">
                                    <div class="bg-black p-2 rounded-end-pill">Details</div>
                                    <div class=" p-2 rounded-start-pill">Share</div>
                                </div>
                            </div>
                        </div>
                        <!-- End Consequat img -->
                        
                        <div class="nam p-0 d-flex col-12 col-md-6 col-lg-6 flex-column justify-content-between">
                            <div class="d-flex justify-content-end p-2"></div>
                            <div>
                                <div class="p-2">
                                    <h5>Nam Lectus Nibh Consequat Aucibus Turpis It Has</h5>
                                </div>
                                <div class="d-flex justify-content-between py-3">
                                    <div class="bg-black p-2 rounded-end-pill">Details</div>
                                    <div class=" p-2 rounded-start-pill">Share</div>
                                </div>
                            </div>
                        </div>
                    </div>
                        <!-- End Nam img -->
                    <div class="row justify-content-center">
                        <div class="bring p-0 col-12 col-md-6 col-lg-6 d-flex flex-column justify-content-between">
                            <div class="d-flex justify-content-end p-2"></div>
                            <div>
                                <div class="p-2">
                                    <h5>Bring Me The Head Of Alfredo Garcia Best Movie In</h5>
                                </div>
                                <div class="d-flex justify-content-between py-3">
                                    <div class="bg-black p-2 rounded-end-pill">Details</div>
                                    <div class=" p-2 rounded-start-pill">Share</div>
                                </div>
                            </div>
                        </div>
                        <!-- End Bring img -->
                        <div class="pump p-0 col-12 col-md-6 col-lg-6 d-flex flex-column justify-content-between">
                            <div class="d-flex justify-content-end p-2"></div>
                            <div>
                                <div class="p-2">
                                    <h5>Pump Action Interaction English Action Movie (2020)</h5>
                                </div>
                                <div class="d-flex justify-content-between py-3">
                                    <div class="bg-black p-2 rounded-end-pill">Details</div>
                                    <div class=" p-2 rounded-start-pill">Share</div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- End Pump img -->
                </div>
            </div>    
        </div>
     </div>
     <!-- End Latest News -->
     <div class="subscribe  justify-content-center flex-wrap">
        <div class="d-flex">
        <input class="search form-control me-2" type="search" placeholder="First Name" aria-label="Search">
        <input class="search form-control me-2" type="search" placeholder="Last Name" aria-label="Search">
        <input class="search form-control me-2" type="search" placeholder="Email Address" aria-label="Search">
        </div>
        <div class="d-flex justify-content-center">
        <button class="btn" type="submit">Subscribe</button>
        </div>
     </div>
     <!-- End Subscribe -->
  </div>
  
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;
 #app_main{
    
    .new_movie_container, .movie_playlist_container, .new_movie_navbar_container, .latest_news_container{
           padding-left: 16%;
           padding-right: 16%;
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
        .new_movie {margin-bottom: 4rem;}
        .photos{
            .left_pic, .right_pic {
                width: 300px;
                height: 350px;
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
                height: 450px;
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
    .movie_playlist_container{
        .you_tube {
           padding-top: 4rem;
           width: 62%;
        }
        .new_movie {
            background-color: rgb(46, 45, 45);
            color: $Cinema_light;
            margin-top: 4rem;

            .new_movie_overflow{
            overflow: auto;
            height: 250px;
            }
        }
    }
    .coming_soon{
        background-image: url(../../src/assets/img/coming-bg.jpg);
        background-position: left;
        width: 100%;
        height: 100%;
        margin-top: 4rem;
        
        .text {
            display: flex;
            flex-direction: column;
            align-items: center;
            color: $Cinema_light;
            padding-top: 6rem;
            padding-bottom: 8rem;
            padding-left: 40%;
            padding-right: 30%;
            span {
                color: $Cinema_primary;
            }
            .text_opacity {
                background-color: rgba(29, 27, 27, 0.692);
                padding-top: 0.5rem;
            }
        }
    }
    .new_movie_navbar_container {
        flex-wrap: wrap;
        
        .nav_bar {
            color: $Cinema_light;
            padding-top: 2rem;

            div {
                padding-right: 2rem;
                cursor: pointer;
                &:hover {
                color: $Cinema_primary;
            }
            }
        }
        .img {
            
            
            .hurry, .animate, .blue, .nulla, .quisque, .new {
                width: 300px;
                height: 400px;
                margin: 2rem;
                color: $Cinema_light;
                background-size: contain;
                cursor: pointer;
                span{
                    color: $Cinema_primary;
                }
                .star {
                    position: absolute;
                    right: 0;
                }
                .hover_green {
                    background-color: $Cinema_primary;
                    display: none;
                }
                .hover {
                    display: none;
                }
                &:hover .hover,
                &:hover .hover_green {
                    display: block;
                    
                }
                
            
            }
            .hurry {
                background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../../src/assets/img/1-234x300.jpg);
                background-size: cover;
                &:hover  {
                    border: 16px solid $Cinema_dark;
                    background: linear-gradient(rgba(0, 128, 0, 0.8), rgba(0, 128, 0, 0)), url(../../src/assets/img/1-234x300.jpg);
                    background-size: cover;
                    }
                }
          
            .animate {
                background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../../src/assets/img/5-229x300.jpg);
                background-size: cover;
                &:hover  {
                    border: 16px solid $Cinema_dark;
                    background: linear-gradient(rgba(0, 128, 0, 0.8), rgba(0, 128, 0, 0)), url(../../src/assets/img/5-229x300.jpg);
                    background-size: cover;
                    }
            }
            .blue {
                background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../../src/assets/img/3-229x300.jpg);
                background-size: cover;
                &:hover  {
                    border: 16px solid $Cinema_dark;
                    background: linear-gradient(rgba(0, 128, 0, 0.8), rgba(0, 128, 0, 0)), url(../../src/assets/img/3-229x300.jpg);
                    background-size: cover;
                    }
            }
            .nulla {
                background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../../src/assets/img/4-229x300.jpg);
                background-size: cover;
                &:hover  {
                    border: 16px solid $Cinema_dark;
                    background: linear-gradient(rgba(0, 128, 0, 0.8), rgba(0, 128, 0, 0)), url(../../src/assets/img/4-229x300.jpg);
                    background-size: cover;
                    }
            }
            .quisque {
                background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../../src/assets/img/3-222x300.jpg);
                background-size: cover;
                &:hover  {
                    border: 16px solid $Cinema_dark;
                    background: linear-gradient(rgba(0, 128, 0, 0.8), rgba(0, 128, 0, 0)), url(../../src/assets/img/3-222x300.jpg);
                    background-size: cover;
                    }
            } 
            .new {
                background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../../src/assets/img/2-216x300.jpg);
                background-size: cover;
                &:hover  {
                    border: 16px solid $Cinema_dark;
                    background: linear-gradient(rgba(0, 128, 0, 0.8), rgba(0, 128, 0, 0)), url(../../src/assets/img/2-216x300.jpg);
                    background-size: cover;
                    }
            }  
        }
    }
    .latest_news_container {
        .latest_news {
            margin-bottom: 4rem;
        }
        .four_squares {
            width:50%;
            
            
        }
        
        .actor {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../../src/assets/img/blog-570x570.jpg);
            background-repeat: no-repeat;
            background-size: cover;
            width: 46%;
            aspect-ratio: 1/1;
            color: $Cinema_light;
            margin-bottom: 1rem;
            &:hover  {
                    border: 16px solid $Cinema_dark;
                    background: linear-gradient(rgba(0, 128, 0, 0.8), rgba(0, 128, 0, 0)), url(../../src/assets/img/blog-570x570.jpg);
                    background-size: cover;
                    }
        }

        .consequat, .nam, .bring, .pump {
            width: 46%;
            aspect-ratio: 1/1;
            color: $Cinema_light;
            margin-left: 1rem;
            margin-bottom: 1rem;
           
        }
        .consequat {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../../src/assets/img/blog2-150x150.jpg);
            background-size: cover;
            &:hover  {
                    border: 16px solid $Cinema_dark;
                    background: linear-gradient(rgba(0, 128, 0, 0.8), rgba(0, 128, 0, 0)), url(../../src/assets/img/blog2-150x150.jpg);
                    background-size: cover;
                    }
            
        }
        .nam {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../../src/assets/img/blog3-150x150.jpg);
            background-size: cover;
            &:hover  {
                    border: 16px solid $Cinema_dark;
                    background: linear-gradient(rgba(0, 128, 0, 0.8), rgba(0, 128, 0, 0)), url(../../src/assets/img/blog3-150x150.jpg);
                    background-size: cover;
                    }
        }
        .bring {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../../src/assets/img/blog4-150x150.jpg);
            background-size: cover;
            &:hover  {
                    border: 16px solid $Cinema_dark;
                    background: linear-gradient(rgba(0, 128, 0, 0.8), rgba(0, 128, 0, 0)), url(../../src/assets/img/blog4-150x150.jpg);
                    background-size: cover;
                    }
        }
        .pump {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(../../src/assets/img/blog5-150x150.jpg);
            background-size: cover;
            &:hover  {
                    border: 16px solid $Cinema_dark;
                    background: linear-gradient(rgba(0, 128, 0, 0.8), rgba(0, 128, 0, 0)), url(../../src/assets/img/blog5-150x150.jpg);
                    background-size: cover;
                    }
        }
    }
    .subscribe {
        background-image: url(../../src/assets/img/form-bg-1.png);
        background-size: cover;
        background-repeat: no-repeat;
        width: 67%;
        height: 100%;
        margin-top: 4rem;
        margin-bottom: 4rem;
        margin-left: 16%;
        padding: 1rem;
        input {
            margin-top: 8rem;
            height: 50px;
        }
        button {
            background-color: $Cinema_dark;
            color: $Cinema_light;
            height: 50px;
            margin-top: 2rem;
            margin-bottom: 6rem;
             &:hover {
                background-color: $Cinema_light;
                color: $Cinema_dark;
             }
        }
    }
 }
</style>


<script>
import SliderComponent from './sliderComponent.vue'

export default {
    name: "MainComponent",
    components: {
        SliderComponent
    },
    data() {
        return{
            movies:[
                {
                title: 'Quisque Auctor Movie In Strack',
                category: 'Coming soon',
                genres: 'Horror, Drama',
                rate: 4/10,
                release: 'Febrary 12, 2016',
                views: 947 ,
                poster_img:'../assets/img/2-1-216x300.jpg',
                icon_square_img:'../assets/img/2-150x150.jpg',
                square_img:'../assets/img/2-300x300.jpg'
                },
                {
                title: 'Hurry Animate Blue Strack New Movie',
                category: 'Top Rating',
                genres: 'Horror, Drama',
                rate: 0/10,
                release: 'Febrary 12, 2016',
                views: 381 ,
                poster_img:'../assets/img/1-234x300.jpg',
                icon_square_img:'',
                square_img:''
                },
                {
                title: 'New movie quisque in Strack',
                category: 'Latest Movie',
                genres: 'Horror, Drama',
                rate: 0/10,
                release: 'Febrary 12, 2022',
                views: 381 ,
                poster_img:'../assets/img/5-238x300.jpg',
                icon_square_img:'../assets/img/5-150x150.jpg',
                square_img:'../assets/img/5-300x300.jpg'
                },
                {
                title: 'New movie action garila english',
                category: 'Latest Movie',
                genres: 'Horror, Drama, adventure',
                rate: 3/10,
                release: 'june 12, 2022',
                views: 381 ,
                poster_img:'../assets/img/3-229x300.jpg',
                icon_square_img:'../assets/img/3-150x150.jpg',
                square_img:'../assets/img/3-300x300.jpg'
                },
                {
                title: 'New action english garila',
                category: 'Latest Movie',
                genres: 'Horror, Drama, adventure',
                rate: 7/10,
                release: 'july 22, 2002',
                views: 335 ,
                poster_img:'../assets/img/3-1-238x300.jpg',
                icon_square_img:'../assets/img/3-1-150x150.jpg',
                square_img:'../assets/img/3-1-300x300.jpg'
                },
                {
                title: 'Animate Blue Strack Movie',
                category: 'Latest Movie',
                genres: 'Horror, adventure',
                rate: 5/10,
                release: 'july 22, 2002',
                views: 335 ,
                poster_img:'../assets/img/5-229x300.jpg',
                icon_square_img:'../assets/img/5-150x150 (1).jpg',
                square_img:'../assets/img/5-300x300 (1).jpg'
                },
                {
                title: 'Animate Black New Movie',
                category: 'Top rating',
                genres: 'Horror, adventure',
                rate: 9/10,
                release: 'july 22, 2012',
                views: 678 ,
                poster_img:'../assets/img/4-229x300.jpg',
                icon_square_img:'',
                square_img:'.jpg'
                },
                {
                title: 'Quisque Red New Movie',
                category: 'Coming soon',
                genres: 'Horror, adventure',
                rate: 5/10,
                release: 'july 09, 2024',
                views: 0 ,
                poster_img:'../assets/img/3-222x300.jpg',
                icon_square_img:'',
                square_img:''
                },
            ],

        news:[
                {
                title: 'Actor the concept movie theory',
                category: 'Latest Movie',
                genres: 'Drama, adventure',
                rate: 5/10,
                release: 'july 22, 2002',
                views: 335 ,
                poster_img:'',
                icon_square_img:'../assets/img/blog-150x150 (1).jpg',
                square_img:'../assets/img/blog-570x570 (1).jpg'
                },
                {
                title: 'Actor Nam Lectus Nibh theory',
                category: 'Latest Movie',
                genres: 'Drama, adventure',
                rate: 5/10,
                release: 'july 22, 2002',
                views: 335 ,
                poster_img:'',
                icon_square_img:'../assets/img/blog2-150x150 (1).jpg',
                square_img:'../assets/img/blog2-570x570 (1).jpg'
                },
                {
                title: 'Nam Lectus Nibh Consequat',
                category: 'Latest Movie',
                genres: 'Drama, adventure',
                rate: 5/10,
                release: 'july 22, 2002',
                views: 335 ,
                poster_img:'',
                icon_square_img:'../assets/img/blog3-150x150 (1).jpg',
                square_img:'../assets/img/blog3-570x570 (1).jpg'
                },
                {
                title: 'Bring me an Head',
                category: 'Latest Movie',
                genres: 'Horror, adventure',
                rate: 5/10,
                release: 'july 22, 2002',
                views: 335 ,
                poster_img:'',
                icon_square_img:'../assets/img/blog4-150x150 (1).jpg',
                square_img:'../assets/img/blog4-570x570 (1).jpg'
                },
                {
                title: 'Pump Avtion Action Interaction',
                category: 'Latest Movie',
                genres: 'Horror, adventure',
                rate: 5/10,
                release: 'july 22, 2002',
                views: 335 ,
                poster_img:'',
                icon_square_img:'../assets/img/blog5-150x150 (1).jpg',
                square_img:'../assets/img/blog5-570x570 (1).jpg'
                },
            ]
        }
    },
    methods: {

    }
}
</script>

<template>

    <main>

        <!-- "WELCOME TO OUR SITE" SECTION -->
        <section id="main-sec1">
            
            <div class="d-flex flex-column align-items-end justify-content-center h-100">
                <div class="middle-height-text position-relative text-center">
                    <h5>Welcome to Our Movie Site</h5>
                    <h2 class="text-uppercase fs-1">our special <span class="text-green">movies</span></h2>
                    <div class="w-50 d-inline-block">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos voluptas maiores non sequi in, ut saepe tenetur assumenda.</div>
                    <div class="mt-3">
                        <a href="#" class="my-btn">Read More</a>
                    </div>
                </div>
                <div id="up-square-chevron">
                    <font-awesome-icon class="p-4" :icon="['fas', 'angle-up']" style="background-color: #182028;" />
                </div>
            </div>
            
        </section>

        <div class="my-container">

            <sliderComponent />

            
            <!-- MOVIE PLAYLIST SECTION  -->
            <section id="main-sec3">

                <div class="section-title mt-4">
                    <div class="row">
                        <div class="col title pb-3 ps-3">
                            <h4>Movie Playlist</h4>
                            <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur, officiis!</div>
                        </div>
                        
                    </div>
                </div>

                <div class="row">
                    <div class="col-8 debug h-100">
                        <div class="box debug bg-black">
                            
                        </div>
                    </div>
                    <div class="col-4 debug h-100">
                        <div class="movie-list debug h-100 overflow-auto">
                            <div class="header p-3">
                                <h6>New Movie</h6>
                                <small>Plying 24</small>
                            </div>
                            <div class="list h-100">

                                <div class="my-card p-3 d-flex w-100">
                                    <div class="movie-icon me-2">
                                        <img src="../assets/img/1-2-150x150.jpg" alt="">
                                    </div>
                                    <div class="">
                                        <h5>Title</h5>
                                        <div class="mb-2">323 views</div>
                                        <div class="d-flex justify-content-between">
                                            <span>date</span>
                                            <span>duration</span>
                                        </div>
                                    </div>
                                </div>
                                <div class="my-card p-3 d-flex w-100">
                                    <div class="movie-icon me-2">
                                        <img src="../assets/img/1-2-150x150.jpg" alt="">
                                    </div>
                                    <div class="">
                                        <h5>Title</h5>
                                        <div class="mb-2">323 views</div>
                                        <div class="d-flex justify-content-between">
                                            <span>date</span>
                                            <span>duration</span>
                                        </div>
                                    </div>
                                </div>
                                <div class="my-card p-3 d-flex w-100">
                                    <div class="movie-icon me-2">
                                        <img src="../assets/img/1-2-150x150.jpg" alt="">
                                    </div>
                                    <div class="">
                                        <h5>Title</h5>
                                        <div class="mb-2">323 views</div>
                                        <div class="d-flex justify-content-between">
                                            <span>date</span>
                                            <span>duration</span>
                                        </div>
                                    </div>
                                </div>
                                <div class="my-card p-3 d-flex w-100">
                                    <div class="movie-icon me-2">
                                        <img src="../assets/img/1-2-150x150.jpg" alt="">
                                    </div>
                                    <div class="">
                                        <h5>Title</h5>
                                        <div class="mb-2">323 views</div>
                                        <div class="d-flex justify-content-between">
                                            <span>date</span>
                                            <span>duration</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            
                        </div>
                    </div>
                </div>

            </section>  
        </div>

        <!-- SECTION "COMING SOON MOVIE" -->
        <section>
            <div class="my-container"></div>
        </section>

        <div class="my-container">

            <!-- NEW MOVIES SECTION  -->
            <section id="sec"></section>

            <!-- LASTEST NEWS SECTION  -->
            <section id="sec"></section>

            <!-- NEWSLETTER FORM BOX  -->
            <section id="sec"></section>
        </div>

    </main>

</template>

<style lang="scss" scoped>

main{

    .section-title{
            padding: 60px 0;

            .title{
                border-left: 2px solid #13BE13;
                border-bottom:1px solid #182028;
            }
        }

    #main-sec1{
        background-image: url(../assets/img/slider-1536x520.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        height:650px;
        overflow: auto;
        position: relative;

        .middle-height-text{
            position: relative;
            right: 200px;

            .my-btn {
                background-color:#13be13;
                border-radius:28px;
                display:inline-block;
                cursor:pointer;
                color:#ffffff;
                font-family:Arial;
                font-size:17px;
                font-weight:bold;
                padding:13px 25px;
                text-decoration:none;
                text-shadow:0px 1px 0px #2f6627;
            }
            .my-btn:hover {
                background-color:#5cbf2a;
            }
            .my-btn:active {
                position:relative;
                top:1px;
            }

        }
        #up-square-chevron{
            position: absolute;
            bottom: 60px;
            right: 50px;
        }
    }
    
    #main-sec3{
        min-height: 1000px;

        .debug{
            min-height: 500px;
            border: 1px solid black;
        }
        >.row{
            height: 500px;
        }
        .movie-list{
            background-color: #182028;

            .header{
                border-bottom: 1px solid rgb(6, 15, 25);
                height: 85px;
            }
            .my-card{

                .movie-icon{
                    width: 100px;
                    height: 100px;
                }
            }
        }
        
    }
    
}

</style>
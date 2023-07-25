<script>
export default {
    name: "MainComponent",
    data() {
    return{

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
                <div class="middle-height-text position-relative">
                    TEXT
                </div>
                <div id="up-square-chevron">
                    FRECCETTA
                </div>
            </div>
            
        </section>

        <div class="my-container">

            <!-- NEW MOVIES SECTION  -->
            <section id="main-sec2">

                <div class="section-title">
                    <div class="row">
                        <div class="col-10 title pb-3 ps-3">
                            <h4>New Movie</h4>
                            <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur, officiis!</div>
                        </div>
                        <div class="col-2">
                            freccette
                        </div>
                    </div>
                </div>
                <div class="movies-carousel">
                    <div class="row g-0">

                        <div class="col">
                            <div class="my-card">
                                <img src="../assets/img/1-234x300.jpg" alt="">
                                <div class="w-100 h-100">
                                    <h4 class="title">title</h4>
                                    <div class="vote">VOTO</div>
                                    <div class="category">categoria</div>
                                    <div class="details card-appendix">
                                        details
                                    </div>
                                    <div class="views card-appendix">
                                        2020
                                    </div>
                                    
                                </div>
                            </div>
                        </div>

                        <div class="col">
                            <div class="my-card active">
                                <img src="../assets/img/2-1-216x300.jpg" alt="">
                            </div>
                            
                        </div>

                        <div class="col">
                            <div class="my-card">
                                <img src="../assets/img/5-238x300.jpg" alt="">
                                
                            </div>
                        </div>

                    </div>
                </div>
                

            </section>

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
            right: 800px;
        }
        #up-square-chevron{
            position: absolute;
            bottom: 60px;
            right: 50px;
        }
    }
    #main-sec2{

        .movies-carousel{

            .my-card{

                // debug
                background-color: pink;
                border: 1px dashed black;
                position: relative;
                
                img{
                    border-radius: 30px;
                    height: 400px;
                }
                >div{
                    padding: 10px;
                    
                }
                div{
                    position: absolute;
                    bottom: 0;
                }
                .vote{
                    top: 7px;
                    right: 12px;
                }
                .title{
                    position: absolute;
                    bottom: 60px;
                }
                .category{
                    bottom: 50px;
                }
                .details{
                    bottom: 25px;
                    left: 0px;
                }
                .views{
                    bottom: 25px;
                    right: 0px;
                }

                
            }
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
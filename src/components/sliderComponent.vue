<script>
export default {
    name: "sliderComponent",
    data() {
    return{

    }
    },
    methods: {

    },
    props: {
        title : String,
        category: String,
        rate : Number,
        views : Number,

    }
}
</script>

<template>

    <!-- NEW MOVIES SECTION  -->
    <section id="main-sec2">

        <div class="section-title my-5">
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

</template>

<style lang="scss" scoped>



#main-sec2{

        .section-title{

            .title{
                border-left: 2px solid #13BE13;
                border-bottom:1px solid #182028;
            }
        }
    .movies-carousel{

        .my-card{

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

</style>
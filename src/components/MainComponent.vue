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
        <section id="main-first-sec">
            
            <div class="d-flex flex-column align-items-end justify-content-center h-100">
                <div class="middle-height-text position-relative">
                    TEXT
                </div>
                <div id="up-square-chevron">
                    FRECCETTA
                </div>
            </div>
            
        </section>

        <div class="container">

            <!-- NEW MOVIES SECTION  -->
            <section id="sec"></section>

            <!-- MOVIE PLAYLIST SECTION  -->
            <section id="sec"></section>
        </div>

        <!-- SECTION "COMING SOON MOVIE" -->
        <section>
            <div class="container"></div>
        </section>

        <div class="container">

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
    

    #main-first-sec{
        background-image: url(../assets/img/slider-1536x520.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        height:650px;
        overflow: auto;
        position: relative;
    }

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

</style>
<script>
import { store } from '../store';

export default {
    name: "sliderComponent",
    data() {
    return{
        // store,
    }
    },
    methods: {

        getImgPath: function(src) {
            console.log(new URL(`${src}`, import.meta.url).href);
            return new URL(`${src}`, import.meta.url).href
        }
    },
    props:{
        movieTitle: String,
        movieCategory: String,
        movieRate: String,
        movieViews: Number,
        moviePoster: String

    },
    computed:{

    },
    created(){
        
    },
}

</script>

<template>

        <div class="col-4">
            <div class="my-card m-3">
                <img :src="getImgPath(moviePoster)"  alt="Immagine mancante">
                <div class="w-100 h-100">
                    <h4 class="title mb-4">{{ movieTitle }}</h4>
                    <div class="vote">{{ movieRate }}</div>
                    <div class="category mb-2">{{ movieCategory }}</div>
                    <div class="details card-appendix p-1 px-2">
                        <a href="#">Details
                        </a>    
                    </div>
                    <div class="views card-appendix p-1 px-2">
                        {{ movieViews }}
                    </div>
    
                    <!-- class="col" v-for="(singleCard , i) in cards" :key="i" -->
                    
                </div>
            </div>
        </div>


</template>

<style lang="scss" scoped>

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
            background-color: rgb(6, 15, 25);
            border-radius: 0 10px 10px 0;
        }
        .views{
            bottom: 25px;
            right: 0px;
            background-color: rgb(6, 15, 25);
            border-radius: 10px 0 0 10px;


        }
}



</style>
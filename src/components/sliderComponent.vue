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
        
    },
    props:{
        movieTitle: String,
        movieCategory: String,
        movieRate: String,
        movieViews: Number,
        moviePoster: String

    },
    computed:{

    }
}
</script>

<template>

        <div class="col-4">
            <div class="my-card">
                <img :src="moviePoster"  alt="">
                <div class="w-100 h-100">
                    <h4 class="title">{{movieTitle}}</h4>
                    <div class="vote">{{ movieRate }}</div>
                    <div class="category">{{ movieCategory }}</div>
                    <div class="details card-appendix">
                        details
                    </div>
                    <div class="views card-appendix">
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
        }
        .views{
            bottom: 25px;
            right: 0px;
        }
}



</style>
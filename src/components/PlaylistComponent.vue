<script>
import { store } from '../store';

export default {
    name: "PlaylistComponent",
    data() {
    return{
        // store,
    }
    },
    methods: {
        
    },
    props:{
        movieTitle: String,
        movieViews: Number,
        movieIcon: String,
        movieRelease: String,

    },
    computed:{

    }
}
</script>

<template>

    <div class="my-card p-3 d-flex w-100">
        <div class="movie-icon me-2">
            <img src="../assets/img/1-2-150x150.jpg" alt="">
        </div>
        <div class="">
            <h6>{{ movieTitle }}</h6>
            <div class="mb-2">{{movieViews + ' views'}}</div>
            <div class="d-flex justify-content-between">
                <span>{{ movieRelease }}</span>
                <span class="text-end">2.30.00</span>
            </div>
        </div>
    </div>

</template>

<style lang="scss" scoped>

            
            .my-card{

                .movie-icon{
                    width: 100px;
                    height: 100px;
                }
            }

</style>
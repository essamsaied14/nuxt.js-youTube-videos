<template>
    <div>
        
        <b-container class="bv-example-row mt-4">
            <h1> All 5 Videos</h1>
                <b-row>
                    <b-col lg="4" class="mt-4" v-for="(val,index) in videoList" :key="index">
                        
                        <video-component :u-video-id="val"></video-component>
                        
                    </b-col>
                </b-row>
        
        </b-container>
    </div>
</template>
<script>
import VideoComponent from '~/components/Video-component.vue'
export default {
    name : "videos-component",
    components: {
        VideoComponent
    },
    computed:{
        videoList(){
            return this.$store.state.videostore.videoList ;
        }
    }
}

</script>

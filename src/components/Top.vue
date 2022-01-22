<template>
    <div id="top">
        <VideoBackground 
          id="bg-video" 
          :src="require('@/assets/video/kkb_low.mp4')" 
          :poster="require('@/assets/image/bg_start.jpeg')">
          <div id="overlay">
            <div id="top-content">
              <b id="top-text">IHR EXPERTE FÜR VERANSTALTUNGSTECHNIK</b>
              <v-btn>
                <img @click="$vuetify.goTo('#over')" id="arrow" src="../assets/image/arrow_down_circle.png" alt="kkb-event">
              </v-btn>
            </div>
          </div>
        </VideoBackground>
    </div>
</template>

<script>

import VideoBackground from 'vue-responsive-video-background-player'

export default {
  name: 'top',
  components: {
    VideoBackground
  }
}
</script>

<style >
    #overlay {
      width: 100%;
      height:100%;
      background-image: url("../assets/image/overlay.png");;
    }
    #bg-video {
      max-height: 600px; 
      height: 600px;
      background-color: black;
    }
    #top-content {
      width: 1000px;
      height: 100%;
      display: inline-block;
      color: white;
      font-size: 50px;
    }
    #top-text {
      position: relative;
      top: 110px;
    }
    #arrow {
      position: relative;
      width:60px;
      top: 45%;
      left: -32%
    }
</style>

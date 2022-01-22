<template>
    <div id="top">
        <VideoBackground 
          id="bg-video" 
          :src="require('@/assets/video/kkb_low.mp4')" 
          style="max-height: 600px; height: 600px;"
          overlay="linear-gradient(to top, rgba(0, 0, 0, 0) 97%, black 100%)">
            <div id="top-content">
              <b id="top-text">IHR EXPERTE FÜR VERANSTALTUNGSTECHNIK</b>
              <v-btn>
                <img @click="$vuetify.goTo('#over')" id="arrow" src="../assets/image/arrow_down_circle.png" alt="kkb-event">
              </v-btn>
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
    #bg-video {
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

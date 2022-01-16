<template>
    <div id="top">
        <VideoBackground id="video" :src="require('@/assets/video/kkb_low.mp4')" style="max-height: 600px; height: 600px;"></VideoBackground>
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
    #video{
        z-index: 0;
        background-color: black;
    }
</style>

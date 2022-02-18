<template>
  <div class="video">
    <iframe
      width="1280"
      height="720"
      src="https://www.youtube.com/embed/w5Dw2mpcf7M"
      title="YouTube video player"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen
    >
    </iframe>
  </div>
</template>

<script>
export default {
  name: 'VideoSection',
  props: {},
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.video {
  padding-top: 10px;
  margin-top: 25px;
  padding-bottom: 25px;
  margin-bottom: 25px;
}
</style>

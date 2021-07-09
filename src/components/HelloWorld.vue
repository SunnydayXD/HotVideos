<template>
  <div class="hello">
    <button type="primary"></button>
    <video src="http://baobab.kaiyanapp.com/api/v1/playUrl?vid=263452&resourceType=video&editionType=default&source=aliyun&playUrlType=url_oss&udid=&f=iphone&u=&vc=0" controls></video>
  </div>
</template>

<script>
export default {
  result: null,
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

video{
  width: 500px;
  height: 500px;
}
</style>

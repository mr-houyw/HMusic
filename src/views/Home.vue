<template>
  <div>
    <div class="swiper">
      <banner></banner>
    </div>
    <newsong v-bind:state="true"></newsong>
  </div>
</template>

<script>
// @ is an alias to /src
import banner from '../components/Banner'
import newsong from '../components/Newsong'
export default {
  name: 'Home',
  components: {
    banner,
    newsong
  }
}
</script>
<style lang="scss" scoped>
div {
  .swiper {
    width: 100%;
    height: 385px;
    // background: gray;
  }
  // bottom: 85px;
}
</style>

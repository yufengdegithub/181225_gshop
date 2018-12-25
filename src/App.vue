<script src="../../../尚硅谷Vue硅谷外卖项目视频/code/gshop-server_final/bin/www"></script>
<template>
    <div id="app">
        <router-view/>
        <FooterGuide v-show="$route.meta.showFooter"/>
    </div>
</template>

<script>
  import FooterGuide from './components/FooterGuide/FooterGuide.vue'
  export default {
    components:{
      FooterGuide
    }
  }
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .app
    width 100%
    height:100%
    background #f5f5f5
</style>

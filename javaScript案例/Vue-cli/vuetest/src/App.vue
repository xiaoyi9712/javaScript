<template>
  <div id="app">
    <home-title></home-title>
    <home-content></home-content>
  </div>
</template>

<script>
  //导入 HomeTitle组件 @表示src所在目录
  import HomeTitle from'@/components/HomeTitle'
  import HomeContent from'@/components/HomeContent'
export default {
  components:{
    HomeTitle,
    HomeContent
  },
}
</script>

<style>
*{
  margin:0;
  padding:0;
}
</style>
<template>
  <div class="header">
    <div class="nav">
      <!--<div class="logo"><a href="/"><img :src="images/logo.png"></a></div>-->
      <div class="nav_icon"></div>
      <div class="side_close"></div>
      <ul>
        <li><router-link to="/">首页/HOME </router-link></li>
        <li><router-link to="/">资讯/NEWS</router-link></li>
        <li><router-link to="/">作品/GALLERY </router-link></li>
        <li><router-link to="/">关于/ABOUT</router-link></li>
        <li><router-link to="/">视频/VIDEO</router-link></li>
        <li><router-link to="/">联系/CONTACT </router-link></li>
      </ul>
      <!--<div class="header_info"><p><img  :src='images/code.jpg'/></p></div>-->
    </div>
  </div>
</template>
<script>
    export default{
        props: {},
        data(){
            return {}
        }
    }
</script>
<style>
</style>

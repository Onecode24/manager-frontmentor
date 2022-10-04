<template>
  <div class="flex my-[30px] justify-between mx-[20px] md:justify-around">
    <div class="logo">
        <img src="../images/logo.svg" alt="">
    </div>
    <div class="menu hidden md:visible md:flex">
      <menu-bar></menu-bar>
    </div>
    <div class="hambuger md:hidden">
        <img src="../images/icon-hamburger.svg" alt="">
    </div>
    <div class="get-started text-center  mb-8 hidden md:visible md:flex  ">
      <button-global>Get Started</button-global>
    </div>
  </div>
</template>

<script>
import MenuBar from './Menu-Bar.vue';
import ButtonGlobal from './global/Button-Global.vue';
export default {
    name: "nav-bar-vue",
    components: { MenuBar,ButtonGlobal }
}
</script>

<style src="../styles/tailwind.css">

</style>
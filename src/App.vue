<template>
  <div class=" ">
    <div class="navbar">
      <nav-bar-vue></nav-bar-vue>
    </div>
    <div class="fisrt-session bg-mobile px-[20px]" :style="{'background-image' : 'url('+image+')'}">
      <first-session-vue></first-session-vue>
    </div>
    <div class="second-session  py-4">
      <second-session-vue></second-session-vue>
    </div>
    <div class="feedback">
      <feedback-article></feedback-article>
    </div>
    <div class="get-started text-center  mb-8 ">
      <button-global >Get Started</button-global>
    </div>
    <div class="bg-[#ff441f] mt-16 text-center text-white px-14 py-20">
      <h1 class=" text-3xl ">Simplify how your teams works today.</h1>
      <button class="text-[#ff441f] font-medium bg-white mt-8 px-5 rounded-[15px] py-1">Get-started</button>
    </div>
    <div class="footer text-white bg-black px-5 py-10">
      <footer-component-vue></footer-component-vue>
    </div>
  </div>

</template>

<script>
import FirstSessionVue from './components/First-Session.vue';
import NavBarVue from './components/Nav-Bar.vue';
import SecondSessionVue from './components/Second-Session.vue';
import FeedbackArticle from './components/Feedback-Article.vue';
import ButtonGlobal from './components/global/Button-Global.vue';
import FooterComponentVue from './components/Footer-Component.vue';
export default {
  name: 'App',
  components:{
    NavBarVue,FirstSessionVue,SecondSessionVue,FeedbackArticle,ButtonGlobal,FooterComponentVue
  },
  data(){
    return{
      image: "'./images/bg-simplify-section-mobile.svg'"
    }
  }

}
</script>

<style
    FirstSessionle src="./styles/tailwind.css">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.bg-mobile{
  background-image: url('./images/bg-simplify-section-mobile.svg');
}
</style>

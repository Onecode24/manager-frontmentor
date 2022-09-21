<template>
  <div class="bg-mobile ">
    <div class="navbar">
      <nav-bar-vue></nav-bar-vue>
    </div>
    <div class="fisrt-session px-[20px]" :style="{'background-image' : 'url('+image+')'}">
      <first-session-vue></first-session-vue>
    </div>
    <div class="second-session  py-4">
      <second-session-vue></second-session-vue>
    </div>
    <div class="feedback">
      <feedback-article></feedback-article>
    </div>
    <div class="get-started">
      
    </div>
  </div>

</template>

<script>
import FirstSessionVue from './components/First-Session.vue';
import NavBarVue from './components/Nav-Bar.vue';
import SecondSessionVue from './components/Second-Session.vue';
import FeedbackArticle from './components/Feedback-Article.vue';
export default {
  name: 'App',
  components:{
    NavBarVue,FirstSessionVue,SecondSessionVue,FeedbackArticle
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

<template>
  <div class="bg-mobile h-[100px]">
    <div class="navbar">
      <nav-bar-vue></nav-bar-vue>
    </div>
  <div class="fisrt-session px-[20px]" :style="{'background-image' : 'url('+image+')'}">
    <first-session></first-session>
    </div>
    <div class="second-session  py-4">
      <second-session></second-session>
    </div>

  </div>
</template>

<script>
import FirstSession from './components/First-Session.vue';
import NavBarVue from './components/Nav-Bar.vue';
import SecondSession from './components/Second-Session.vue';
export default {
  name: 'App',
  components:{
    NavBarVue,FirstSession,SecondSession
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

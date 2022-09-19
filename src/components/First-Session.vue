<template>
  <div class="">
    <div class="svg">
        <img src="../images/illustration-intro.svg" alt="">
    </div>
    <div class="descrption text-center">
        <h1 class="text-3xl font-bold text-title mb-2">Bring everyone together to build better products:</h1>
        <p class="text-content">Manage makes it simple dor software teams to plan day-to-day taks while keeping the larger teams goals in view</p>
    </div>
    <div class="get-started text-center my-7 blur-[0.65px]">
      <button-global>Get Started</button-global>
    </div>
  </div>
</template>

<script>
import ButtonGlobal from './global/Button-Global.vue';
export default {
  name: 'First-session',
    components: { ButtonGlobal }
}
</script>

<style>

</style>
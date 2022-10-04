<template>
  <div class="md:mx-32 md:flex justify-around mt-10">
    <div class="svg order-last md:w-[70%]">
        <img src="../images/illustration-intro.svg" alt="">
    </div>
    <div class="">
      <div class= "descrption text-center md:w-[60%] md:text-left " >
        <h1 class="text-3xl md:text-[2.75rem] leading-[2.75rem] font-bold text-title mb-2 md:mb-8">Bring everyone together to build better products</h1>
        <p class="text-content ">Manage makes it simple dor software teams to plan day-to-day taks while keeping the larger teams goals in view</p>
      </div>
      <div class="get-started text-center md:text-lg md:w-[60%] md:text-left my-7 blur-[0.65px]">
        <button-global>Get Started</button-global>
      </div>
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
  .line{
    line-height: 3rem;
  }
</style>
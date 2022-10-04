<template>
  <button class="text-white py-2 px-6 bg-[#ff441f] rounded-[40px] shadow-lg shadow-[#ff5c3c9e]">
    <slot></slot>
  </button>
</template>

<script>
export default {
    props:{
      shadow: {
        type: Boolean,
        default: true,
      }
    }
}
</script>

<style>

</style>
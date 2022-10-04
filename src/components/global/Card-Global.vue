<template>
    <div class="my-12">
      <div class="title">
        <div class="text-white py-[6px] px-5 bg-[#ff441f] rounded-[40px] w-14 absolute">
            0{{tag}}
        </div>
        <div class="bg-[#ffd7bd] md:bg-white pl-12 py-[6px]  text-title font-bold  ml-5">
           {{title}}
        </div>
      </div>
      <div class="my-3 text-content text-black text-sm md:ml-16 md:mr-44">
         {{description}}
      </div>
      </div>
</template>

<script>

export default {
    name: 'Card-Global',
    data(){
        
    },
    props:{
      tag: {
        type: Number,
        require: true,
        default: 0
      },
      description:{
        type: String,
        require: true,
        default: "Description"
      },
      title:{
        type: String,
        require: true,
        default: "Title"
      }  
    },

}
</script>

<style>

</style>
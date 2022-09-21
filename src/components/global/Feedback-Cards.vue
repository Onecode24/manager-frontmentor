<template>
 <div class=" my-16">
    <div class="profil">
        <img :src="require(`@/images/${image}`)" alt="" class="rounded-full absolute mt-[-40px] ml-[40%] w-20 h-20">
    </div>
    <div class="cardinfo px-8 mx-10 pt-16 bg-gray-200">
        <h2 class="text-lg font-semibold">{{name}}</h2>
        <p class="text-base text-gray-400 py-4">{{body}}</p>
    </div>
 </div> 
</template>

<script>
export default {
    props: {
        image: {
            type: String,
            required: true
        },
        name: {
            type: String,
            required: true
        },
        body: {
            type: String,
            required: true
        }
    }
}
</script>

<style>

</style>
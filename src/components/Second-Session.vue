<template>
    <div class="md:flex ">
        <div class="description text-center my-10 px-[35px] md:ml-28 md:text-left">
            <h1 class="text-2xl font-bold text-title mb-2 px-5 md:text-[2rem] leading-[2.75rem]">What's different about Manage?</h1>
            <p class="text-content text-sm md:w-[75%] md:px-5 md:mt-8 md:text-base">Manage provides all the functionality your team needs, without the complexity. Our software is talor-made for modern digital product teams.</p>
        </div>
        <div class="px-[20px]">
            <template v-for=" (card,index) in cards" :key="card.title">
                <card-global :tag="Number(index+1)" :title="card.title" :description="card.description"></card-global>
            </template>
        </div>
    </div>
</template>

<script>
import CardGlobal from "./global/Card-Global.vue"

export default 
  {
    name: 'Second-session',
    components: { CardGlobal },
    data(){
        return{
            cards: [
                {title: "Track company-wide progress",description: " See how your day-to-day taks fit into the wider vision. Go from tracking  progress at the milestone level all the way done to the smallest of details. Never lost sight of the bigger picture again."},
                {title: "Track company-wide progress",description: " See how your day-to-day taks fit into the wider vision. Go from tracking  progress at the milestone level all the way done to the smallest of details. Never lost sight of the bigger picture again."},
                {title: "Track company-wide progress",description: " See how your day-to-day taks fit into the wider vision. Go from tracking  progress at the milestone level all the way done to the smallest of details. Never lost sight of the bigger picture again."},
            ]
        }
    }
}
</script>

<style>

</style>
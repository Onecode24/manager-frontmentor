  <template>
    <div class="text-center">
        <h1 class="text-2xl font-bold text-title mb-2 px-5">What they've said</h1>
        <Splide :options="{ rewind: true, autoplay: true }" >
            <SplideSlide>
                <feedback-cards image="avatar-ali.png" body='"We have been able to cancel so many other subscriptions since using Manage. there is no more cross-channel confusion and everyone is much more focused."' name="Ali Bravo"></feedback-cards>
            </SplideSlide>
            <SplideSlide>
                <feedback-cards image="avatar-anisha.png" body='"We have been able to cancel so many other subscriptions since using Manage. there is no more cross-channel confusion and everyone is much more focused."' name="Anisha Li"></feedback-cards>
            </SplideSlide>
            <SplideSlide>
                <feedback-cards image="avatar-richard.png" body='"We have been able to cancel so many other subscriptions since using Manage. there is no more cross-channel confusion and everyone is much more focused."' name="richard Watts"></feedback-cards>
            </SplideSlide>
            <SplideSlide>
                <feedback-cards image="avatar-shanai.png" body='"We have been able to cancel so many other subscriptions since using Manage. there is no more cross-channel confusion and everyone is much more focused."' name="Shanai Stones"></feedback-cards>
            </SplideSlide>
        </Splide>
    </div>
</template>

<script>
    import FeedbackCards from './global/Feedback-Cards.vue';
    import { Splide, SplideSlide } from '@splidejs/vue-splide';
    import '@splidejs/vue-splide/css';
export default {
    components:{
    FeedbackCards,
    Splide,
    SplideSlide,
}
}
</script>

<style>

</style>
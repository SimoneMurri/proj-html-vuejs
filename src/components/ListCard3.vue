<template lang="">
    <section class="cards">
        <CardElement v-for="card in cardList"
                :imageSrc="card.src"
                :nome="card.name"
        />
    </section>
</template>
<script>
import CardElement from './CardElement.vue';

export default {
    name: 'ListCard3',
    data() {
        return {
            cardList: [
            {
                    src: "src/assets/images/column3-image1.jpg",
                    name: 'Low Oil Prices'
                },
                {
                    src: "src/assets/images/column3-image2.jpg",
                    name: 'Cost Of Divorce'
                },
                {
                    src: "src/assets/images/column3-image3.jpg",
                    name: '2015 Tax Lows'
                },
                {
                    src: "src/assets/images/column3-image4.jpg",
                    name: 'Surveys Matter'
                },
                {
                    src: "src/assets/images/column3-image5.jpg",
                    name: 'In-House Work'
                },
                {
                    src: "src/assets/images/column3-image6.jpg",
                    name: 'Obama Care'
                },
            ]
        }
    },
    components: {
        CardElement
    }
}
</script>
<style lang="scss" scoped>

.cards{
    display: flex;
    flex-direction: column;
    
}
</style>
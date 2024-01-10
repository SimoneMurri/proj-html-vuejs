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
    name: 'ListCard2',
    data() {
        return {
            cardList: [
                {
                    src: "src/assets/images/column2-image1.jpg",
                    name: 'Tax Litigation'
                },
                {
                    src: "src/assets/images/column2-image2.jpg",
                    name: 'Aquisitions'
                },
                {
                    src: "src/assets/images/column2-image3.jpg",
                    name: 'Financial Advice'
                },
                {
                    src: "src/assets/images/column2-image4.jpg",
                    name: 'International'
                },
                {
                    src: "src/assets/images/column2-image5.jpg",
                    name: 'Oil And Gas'
                },
                {
                    src: "src/assets/images/column2-image6.jpg",
                    name: 'Capital Markets'
                },
                
            ],
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
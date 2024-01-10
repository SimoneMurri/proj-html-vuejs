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
    name: 'ListCard',
    data() {
        return {
            cardList: [
                {
                    src: "src/assets/images/column1-image1.jpg",
                    name: 'Deborah Brown',
                },
                {
                    src: "src/assets/images/column1-image2.jpg",
                    name: 'Allen Lucas'
                },
                {
                    src: "src/assets/images/column1-image3.jpg",
                    name: 'Muriel Potter'
                },
                {
                    src: "src/assets/images/column1-image4.jpg",
                    name: 'ken Douglas'
                },
                {
                    src: "src/assets/images/column1-image5.jpg",
                    name: 'Loretta Harris'
                },
                {
                    src: "src/assets/images/column1-image6.jpg",
                    name: 'Phill Russell'
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
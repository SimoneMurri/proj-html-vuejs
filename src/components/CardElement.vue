<template lang="">
    <article>
            <img :src="imageSrc" alt="">
            <p>{{ nome }}</p>
    </article>
</template>
<script>
export default {
    name: 'CardElement',
    props: [
        'imageSrc',
        'nome'
    ]
}
</script>
<style lang="scss" scoped>
article{
        background-color: rgba(211, 211, 211, 0.4);
        width: 80%;
        text-align: center;
        font-size: 10px;
        padding: 20px;
        margin-bottom: 1rem;
        display: flex;
        flex-direction: row;
        margin-right: 10rem;


        img{
            width: 20%;
        }
    }

    p{
        padding-top: 1rem;
        padding-left: .5rem;
    }
</style>
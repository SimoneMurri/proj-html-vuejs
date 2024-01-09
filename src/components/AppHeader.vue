<template lang="">
    <div class="header">
        <span>Avada e associates legal team announce deal to open up oil & gas</span>
        <span>
            <i class="fa-brands fa-square-facebook"></i>
            <i class="fa-brands fa-square-twitter"></i>
            <i class="fa-brands fa-square-instagram"></i>
            <i class="fa-brands fa-square-youtube"></i>
        </span>    
    </div>
    <div class="header-image-container">
        <img class="header-image" src="../assets/images/video_law_home_preview.jpg" alt="">
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>

.header-image-container{
    max-width: 100%;
    height: 400px;
    overflow: hidden;
}

.header-image {
    width: 100%;
    height: auto;
    display: block;
}
.header{
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    align-items: center;
    padding: 0rem 20rem;
    font-size: 12px;
    margin: .5rem 0rem;
}

.fa-brands {
    color: #55A098;
    margin-right: .25rem;
    font-size: 20px;
}
</style>
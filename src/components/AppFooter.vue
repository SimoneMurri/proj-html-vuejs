<template lang="">
    <div class="container-img">
        <div class="content-img">
            <h3>LET'S WORK TOGETHER</h3>
            <p>We have worked with Avada Law for the past 15 years. As we have grown and evolved, what i have valued most about our relationship is that Avada Low know us and our business.</p>
            <button>MAKE ENQUIRY</button>
        </div>
  </div>
  <span class="call"><strong>CALL OUR EXPERT TODAY 1.800.555.6789</strong></span>
  <div class="footer">
        <span class="color-lg">© Copyright 2012-2020 | Avada Theme by Theme Fusion | All Rights Reserved | Powered by WordPress</span>
        <div>
            <i class="fa-brands fa-square-facebook"></i>
            <i class="fa-brands fa-square-twitter"></i>
            <i class="fa-brands fa-square-instagram"></i>
            <i class="fa-brands fa-square-youtube"></i>
        </div>    
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
.container-img { 
  width: 100%;
  height: 400px; 
  background-image: url('../assets/images/where-we-work-parallax.jpg');
  background-size: cover; 
  background-position: center; 
  margin-bottom: 2rem;
}

.content-img { 
padding-top: 5rem;
text-align: center;
color: white; 
position: absolute;
}

p{
    font-size: 14px;
    padding-top: 5rem;
    padding-left: 20rem;
    padding-right: 20rem;
}

button {
    background-color: #55A098;
    color: white;
    padding: 10px 20px;
    border: none;
    position: absolute; 
    top: 120%;
    left: 46%;
    font-size: 10px;
}

.call {
    font-size: 12px;
    padding-left: 20rem;
}

.footer{
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    align-items: center;
    padding: 0rem 20rem;
    font-size: 12px;
    margin: 2rem 0rem;
}

.color-lg {
    color: rgb(184, 179, 179);
}

.fa-brands {
    padding-right: .25rem;
    color: #55A098;
    font-size: 20px;
}
</style>
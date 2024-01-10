<template lang="">
  <div class="container">
    <div class="content">
      <div class="column">
        <h4>WHO WE ARE</h4>
        <p>Nullam fringilla tristique edit id varius. Nulla lacinia quam nec venenatis dignissim. Vivamous volutpat tempus semper. Cras feugiat mi sit amet risus consectetur.</p>
        <button class="btn-learn">LEARN MORE</button>
      </div>
      <div class="column">
        <h4>WHAT WE DO</h4>
        <p>Nullam fringilla tristique edit id varius. Nulla lacinia quam nec venenatis dignissim. Vivamous volutpat tempus semper. Cras feugiat mi sit amet risus consectetur.</p>
        <button class="btn-learn">LEARN MORE</button>
      </div>
      <div class="column">
        <h4>WHERE WE WORK</h4>
        <p>Nullam fringilla tristique edit id varius. Nulla lacinia quam nec venenatis dignissim. Vivamous volutpat tempus semper. Cras feugiat mi sit amet risus consectetur.</p>
        <button class="btn-learn">LEARN MORE</button>
      </div>
    </div>
  </div>
  <div class="second-container">
    <div class="content">
        <div class="columns">
            <i class="fa-solid fa-check"></i>
            <h5>A GLOBAL VIEW</h5>
            <p>Nullam fringilla tristique edit it varius ipsums. Lorem lacinia quam nec venenatis sadips dignissim.</p>
        </div>
        <div class="columns">
            <i class="fa-solid fa-check"></i>
            <h5>EXPERT LOWERS</h5>
            <p>Nullam fringilla tristique edit it varius ipsums. Lorem lacinia quam nec venenatis sadips dignissi.m</p>
        </div>
        <div class="columns">
            <i class="fa-solid fa-check"></i>
            <h5>CLIENT FOCUS</h5>
            <p>Nullam fringilla tristique edit it varius ipsums. Lorem lacinia quam nec venenatis sadips dignissim.</p>
        </div>
        <div class="columns">
            <i class="fa-solid fa-check"></i>
            <h5>LOCAL KNOWLEDGE</h5>
            <p>Nullam fringilla tristique edit it varius ipsums. Lorem lacinia quam nec venenatis sadips dignissim.</p>
        </div>
    </div>
  </div>
  <div class="bg-green">
    <div class="questions">
        <h3 class="p-top">QUESTIONS ABOUT A JUDICAL ISSUE? ASK OUR EXPERTS.</h3>
        <button>ASK AN EXPERT</button>
    </div>
  </div>
  <div class="global">
    <h4 class="title-global">GLOBAL CHALLENGE. WORLD CLASS RESPONSE</h4>
    <div class="list-card">
        <div>
            <h4 class="our-title">OUR PEOPLE</h4>
            <ListCard/>
        </div>
        <div>
            <h4 class="our-title">OUR PRACTISE AREA</h4>
            <ListCard2/>
        </div>
        <div>
            <h4 class="our-title">OUR PUBLICATIONS</h4>
            <ListCard3/>
        </div>
    </div>
  </div>
  <div class="container-img">
    <div class="content-img">
      <img src="../assets/images/envato-logo.png" alt="Logo">
      <p><i>"We have worked with Avada Law for the past 15 years. As we have grown and evolved, what i have valued most about our relationship is that Avada Low know us and our business"</i></p>
      <h5 class="nigel">Nigel Rawlinson • Senior Partner</h5>
    </div>
  </div>
  <div class="container-ipe">
    <div class="content-ipe">
      <div class="column-ipe">
        <img src="../assets/images/law_7.jpg" alt="">
        <h4>INTERNATIONAL</h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
      </div>
      <div class="column-ipe">
        <img src="../assets/images/law_8.jpg" alt="">
        <h4>PARTNERSHIP</h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
      </div>
      <div class="column-ipe">
        <img src="../assets/images/law_3.jpg" alt="">
        <h4>EXCELLENGE</h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
      </div>
    </div>
  </div>
</template>
<script>
import ListCard from './ListCard.vue'
import ListCard2 from './ListCard2.vue'
import ListCard3 from './ListCard3.vue'
export default {
    components:{
        ListCard,
        ListCard2,
        ListCard3
    }
}
</script>
<style lang="scss" scoped>
.container {
    background-color: #f5f5f5;
    padding: 6rem;
    height: 500px;
}

.second-container {
    background-color: white;
    padding: 5rem;
    height: 300px;
}

.content {
    display: flex;
    justify-content: center;
}

.column {
    border-top: 5px solid #55A098;
    padding: 2rem 2rem;
    background-color: white;
    text-align: center;
    height: 250px;
    border-left: 1px solid lightgray;
    border-bottom: 1px solid lightgray;
    border-right: 1px solid lightgray;
    width: 270px;
    position: relative;
}

.columns {
    padding: .25rem 2rem;
    background-color: white;
    text-align: center;
    width: 220px;
}

p{
    padding-top: 1rem;
    font-size: 12px;
    line-height: 20px;
}

.btn-learn {
    background-color: #2b313c;
    color: white;
    padding: 10px 20px;
    border: none;
    position: absolute; 
    bottom: 23px;
    left: 30%;
    font-size: 10px;
}

.fa-solid{
    color: #55A098;
    padding-bottom: 1rem;
}
.bg-green {
    background-color: #55A098;
    height: 150px;
    width: 100%;
    padding: 0rem 20rem;
}

.p-top{
    padding-top: 4rem;
}
.questions {
    color: white;
    display: flex;
    
    flex-direction: row;
    justify-content: space-between;
}

button{
    background-color: rgba(255, 255, 255, 0.1);
    border: none;
    color: white;
    padding: 15px;
    margin-top: 3.25rem;
    font-size: 10px;
}
.global{
    background-color: white;
    padding: 8rem;
    height: 1050px;
}
.title-global{
    text-align: center;
    padding-bottom: 7rem;
}

.list-card{
    display: flex;
    flex-direction: row;
    padding-left: 4rem;
}

.our-title{
    padding-bottom: 1.5rem;
}

.container-img {
  position: relative; 
  width: 100%;
  height: 300px; 
  background-image: url('../assets/images/showeare-parallax.jpg');
  background-size: cover; 
  background-position: center; 
}

.content-img {
  position: absolute; 
  top: 50%; 
  left: 50%;
  transform: translate(-50%, -50%); 
  text-align: center;
  color: white; 
}

.nigel{
    padding-top: 2rem;
}

div.container-ipe div.content-ipe div.column-ipe img {
    width: 200px;
    padding-bottom: 1rem;
}

.container-ipe {
    background-color: #f5f5f5;
    padding: 6rem;
    height: 600px;
}

.content-ipe {
    display: flex;
    justify-content: center;
}

.column-ipe {
    border-top: 5px solid #55A098;
    padding: 2rem 2rem;
    background-color: white;
    text-align: center;
    height: 400px;
    border-left: 1px solid lightgray;
    border-bottom: 1px solid lightgray;
    border-right: 1px solid lightgray;
    width: 270px;
    position: relative;
}
</style>
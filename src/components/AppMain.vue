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
</template>
<script>
export default {
    
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
</style>
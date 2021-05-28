<template>
    <div class="main">
      <div class="phone"></div>
      <div class="crisps"></div>


<div class="container-content">
    <div class="helper-text">Your daily pick-me-up</div>
    <div class="title">How does it work.</div>
    <div class="description">Start choosing your favorite teas and snacks in your nearby stores and place your orders, accumulate points, share gifts and teas with your friends and co-workers, and finally use our T-Pass to get your free drinks.</div>
</div>

    </div>
</template>

<style scoped>
.helper-text{
    font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 18px;
line-height: 18px;
/* identical to box height, or 100% */


color: #576D81;
}
.title{
    margin-top: 30px;
    font-family: Roboto;
font-style: normal;
font-weight: 900;
font-size: 40px;
line-height: 55px;
/* identical to box height, or 138% */


color: #0F2336;
}
.description{
    margin-top: 20px;
    font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 24px;
/* or 150% */


color: #576D81;

}
.container-content{
  padding: 100px 50px 60px 50%;
}
.main   {
    background:url("../assets/cup.png") no-repeat;
    height: 540px;
    width: 100%;
    border-radius: 15px;
    background-position:center left ;
    background-color: #ebeeee;
}
.phone{
    height: 600px;
    width: 300px;
    margin-left: 100px;
    background:url("../assets/phone.png") no-repeat,url("../assets/phone1.png") no-repeat;
    background-position: center,center;
    background-size: cover,auto;
    position: absolute;
    top:880px;
    border-radius:50px;
}
.crisps{
     background:url("../assets/crisps.png") no-repeat;
     width: 233px;
     height: 117px;
     background-size: cover;
     z-index: 10;
       top:1400px;
     position: absolute;
     margin-left: 300px;

}
</style>
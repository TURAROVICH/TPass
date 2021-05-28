<template>
    <div class="main">

<div class="container-content">
    <div class="helper-text">Your daily pick-me-up</div>
    <div class="title">How does it work.</div>
    <div class="description">Start choosing your favorite teas and snacks in your nearby stores and place your orders, accumulate points, share gifts and teas with your friends and co-workers, and finally use our T-Pass to get your free drinks.</div>
</div>
<div class="product"></div>
<div class="phone"></div>

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
  padding: 100px 50% 60px 50px;
}
.main   {
    margin: 90px 0px;
    background:url("../assets/djus.png") no-repeat;
    height: 540px;
    width: 100%;
    border-radius: 15px;
    background-position:center right ;
    background-color: #ebeeee;
}

.phone{
    height: 600px;
    width: 300px;
    margin-left: 100px;
    background:url("../assets/frame1.png") no-repeat;
    background-position: center right;
    /* position: absolute;
    top:100%; */
    background-size: cover;
    margin-left: 550px;
    margin-top: -870px;
}
.product{
      height: 600px;
    width: 300px;
    margin-left: 100px;
    background:url("../assets/img4.png") no-repeat;
    background-position: center right;
    /* background-size: cover; */
    margin-left: 290px;
    margin-top: -190px;
}
</style>
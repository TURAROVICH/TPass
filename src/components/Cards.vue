<template>
    <div class="main">
        <div class="container">

            <div class="product">
                <div class="icon">
                    <img src="../assets/Group2.png" alt="">
                </div>
                <div class="title">Order ahead, skip the line</div>
                <div class="description">
Feel like a rock star when you bypass the line and save a bunch of time.
                </div>
            </div>

    <div class="product">
                <div class="icon">
                    <img src="../assets/Group2.png" alt="">
                </div>
                <div class="title">Bonus and discounts</div>
                <div class="description">
You can enjoy lots of discounts from the selected stores, or accumulate points.
                </div>
            </div>

                <div class="product">
                <div class="icon">
                    <img src="../assets/Group3.png" alt="">
                </div>
                <div class="title">Share with your friends</div>
                <div class="description">
Send gifts to your friends and family, and pick up for your coworkers when they can't get away .
                </div>
            </div>

        </div>
    </div>
</template>

<style scoped>
.main{
    margin:50px 0px;
}
.container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}
.icon{
    width: 105px;
    height: 105px;
    border-radius: 50%;
   background: linear-gradient(160.47deg, rgba(0, 201, 201, 0.147) 15.15%, rgba(0, 201, 201, 0.699) 93.19%);
     display: flex;
     justify-content: center;
     align-items: center;
}
.title{
    font-family: Roboto;
font-style: normal;
font-weight: bold;
font-size: 25px;
line-height: 32px;
/* identical to box height, or 130% */

letter-spacing: 0.2px;

color: #0F2336;
width: 296px;
}
.description{
    font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 24px;
width: 296px;
color: #576D81;
}
</style>
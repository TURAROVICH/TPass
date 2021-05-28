<template>
    <div class="main">
        <div class="content_container">
            <div class="text">
Order ahead and earn rewards for every purchase
            </div>
            <div class="button">
               <p>Discover how </p><img src="../assets/Arrow.png" alt="">
            </div>
        </div>

        <div class="imgs">

        </div>
    </div>
</template>
<style scoped>
.main{
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}
.imgs{
    background:url("../assets/people.png") center center no-repeat, url("../assets/Group1.png") 200px 70px no-repeat,url("../assets/Group.png") bottom right no-repeat,url("../assets/Vector1.png") center center no-repeat;
    width: 100%;
    height:80vh ;
  background-size: auto,auto,auto,cover;
}
.text::first-line{
    color: #00CCCC;
}
.text{
    font-family: Roboto;
font-style: normal;
font-weight: bold;
font-size: 55px;
line-height: 76px;
/* identical to box height, or 138% */

letter-spacing: 1.11px;

color: #0F2336;
width: 500px;
}
.button{
    margin-top: 30px;
    width: 208px;
    height: 60px;
    background: #00CCCC;
border: 1px solid #00CCCC;
box-sizing: border-box;
box-shadow: 0px 3px 18px rgba(0, 201, 201, 0.55);
border-radius: 14px;
display: flex;
align-items: center;
justify-content: center;
cursor: pointer;

}

.button p{
    font-family: Roboto;
font-style: normal;
font-weight: bold;
font-size: 18px;
line-height: 22px;
/* identical to box height, or 120% */


color: #0F2336;
}
</style>
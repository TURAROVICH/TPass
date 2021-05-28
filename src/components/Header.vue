<template>
    <div class="main">
        <div class="container">
            <div class="logo">
                 <img src="../assets/Vector.png" alt="">
                <div class="logo-text">
                    <div>T</div><div class="dot"></div><div>Pass</div>
                </div>
            </div>

            <div class="support">
                <div class="support-text">Stores</div>
                <div class="support-text">Help & Support</div>
                <div class="btn"><p>Download</p></div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.btn{
    background: #0F2336;
border: 1px solid #0F2336;
box-sizing: border-box;
border-radius: 8px;
display: flex;
align-items: center;
justify-content: center;
width: 122px;
height: 50px;
cursor: pointer;
}
.btn p{
    font-family: Roboto;
font-style: normal;
font-weight: bold;
font-size: 14px;
line-height: 17px;
/* identical to box height, or 120% */


color: #FFFFFF;
}
.support{
display: flex;
align-items: center;
justify-content: space-evenly;
width: 400px;
font-style: normal;
font-weight: bold;
font-size: 14px;
line-height: 17px;
color: #0F2336;
}
.logo-text{
    font-weight: bolder;
    font-size: 35px;
    color: #0F2336;
   display: flex;
    align-items: center;
    justify-content: center;
}
.container{
    margin: 20px 0;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.logo{
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 170px;
}
.dot{
    background: linear-gradient(90deg, #59C4C9 0.12%, #41B1BE 37.08%, #0F8BA8 100%);
    width: 10px;
    height: 10px;
    border-radius: 50%;
    margin:22px 5px 0px 0px
}
@media screen and (max-width:994px) {
    .support{
        width: 500px;
    }
    .logo{
    width: 100px;

    }
}
</style>
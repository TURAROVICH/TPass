<template>
    <div class="main">
        <div class="img">
            <img src="../assets/Group5.png" alt="">
        </div>
        <div class="logo">
                <img src="../assets/Vector.png" alt="">
                <div class="logo-text">
                    <div>T</div><div class="dot"></div><div>Pass</div>
                </div>
        </div>

        <div class="helper">
             <div class="company">
                 <div class="title">Company</div>
                 <div class="list">
                     <ul>
                         <li>Merchant Portal</li>
                     </ul>
                 </div>
             </div>

             <div class="support">
                 <div class="title">Support</div>
                 <div class="list">
                     <ul>
                         <li>FAQ</li>
                         <li>Terms of Service</li>
                         <li>Privacy Policy</li>
                     </ul>
                 </div>
             </div>

             <div class="folow-us">
                 <div class="title">Follow Us</div>
                 <div class="list">
                     <ul>
                         <li>Twitter</li>
                         <li>Instagram</li>
                         <li>Facebook</li>
                     </ul>
                 </div>
             </div>
        </div>

        <div class="img">
            <img src="../assets/Group6.png" alt="">
            <img id="abs" src="../assets/Group7.png" alt="">
        </div>
    </div>
</template>

<style scoped>
.list ul li{
    
font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 20px;
/* or 143% */

letter-spacing: 0.39px;

color: rgba(255, 255, 255, 0.7);
}
.title{
    font-family: Roboto;
font-style: normal;
font-weight: bold;
font-size: 12px;
line-height: 20px;
/* or 167% */

letter-spacing: 0.1px;

color: #00CCCC;
}
li{
    list-style: none;
}
#abs{
    position: absolute;
    right: 0px;
    top: 3490px;
}
.helper{
    display: flex;
    align-items: flex-start;
    justify-content:space-around;
    width: 500px;
}
.logo img{
    background: #fff;
    color: #fff;
    border-radius: 50px;
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
.logo-text{
    font-weight: bolder;
    font-size: 35px;
    color:#fff;
   display: flex;
    align-items: center;
    justify-content: center;
}
.main{
    height: 280px;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background: #0F2336;
}
</style>
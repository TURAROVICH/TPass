<template>
    <div class="main">
        <div class="container">
            <div class="icon"><img src="../assets/Group4.png" alt=""></div>
            <div class="title">
                   Enjoy your afternoon tea with a snack
            </div>

            <div class="form">
                <input type="text" placeholder="Enter mobile number">
                <button class="btn">Send link</button>
            </div>

              <div class="cards">
                     <div class="card">
                         <div class="text-container">
                             <div class="helper-text">Download on the</div>
                             <div class="text">App Store</div>
                         </div>
                     </div>
                      <div class="card">
                         <div class="text-container">
                             <div class="helper-text">Get it on</div>
                             <div class="text">Google Play</div>
                         </div>
                     </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.cards{
    margin: 30px 0px;
    display: flex;
    align-items: center;
    justify-content: space-around;
    width: 400px;
}
.card{
    width: 185px;
    height: 60px;
    background: #240C39;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 15px;
    color:#fff;
}
.helper-text{
    font-size: 12px;
}
.text{
     font-size: 20px;
}
.title{
    font-family: Roboto;
font-style: normal;
font-weight: 900;
font-size: 50px;
line-height: 60px;
width: 500px;
text-align: center;
margin-top: 30px;
color: #0F2336;
}
.form input{
    text-align: center;
    width: 394px;
    height: 55px;
    border: none;
    background: #C7CFCF;
}
.form button{
    width: 156px;
    height: 55px;
    background: #00CCCC;
border: 1px solid #00CCCC;
box-sizing: border-box;
border-radius: 14px;
margin-left: 10px;
font-family: Roboto;
font-style: normal;
font-weight: bold;
font-size: 18px;
line-height: 22px;
/* identical to box height, or 120% */

text-align: center;

color: #0F2336;
}
.main{
    margin: 70px 0px;
}
.container{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}
</style>
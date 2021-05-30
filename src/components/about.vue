<template>
    <div class="main">
        <div class="cards">
                 <div class="card">
                     <div class="card-container">
                    <div class="title-container">
                    <div class="icon"><img src="../assets/Frame.png" alt=""></div>
                    <div class="title">Loyalty Points</div>
                    </div>

                    <div class="container">
                        <div class="description">
                      Collect points on each store and redeem them to change for Teas.
                        </div>
                    </div>
                    </div>
                 </div>

                    <div class="card">
                     <div class="card-container">
                    <div class="title-container">
                    <div class="icon"><img src="../assets/Vector4.png" alt=""></div>
                    <div class="title">Loyalty Points</div>
                    </div>

                    <div class="container">
                        <div class="description">
                       Collect points on each store and redeem them to change for Teas.
                        </div>
                    </div>
                    </div>
                 </div>

                    <div class="card">
                     <div class="card-container">
                    <div class="title-container">
                    <div class="icon"><img src="../assets/Vector5.png" alt=""></div>
                    <div class="title">Loyalty Points</div>
                    </div>

                    <div class="container">
                        <div class="description">
Collect points on each store and redeem them to change for Teas.
                        </div>
                    </div>
                    </div>
                 </div>

             
        </div>



                 <div class="bg-img">
                      <img src="../assets/about-bg.png" alt="">
                 </div>
    </div>
</template>
<style scoped>

.bg-img{
    margin-top: -100px;
}
.cards{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}
.container{
    display: flex;
    align-items: flex-end;
    justify-content: flex-end;
}
.title{
    font-family: Roboto;
font-style: normal;
font-weight: bold;
font-size: 25px;
line-height: 25px;
/* identical to box height, or 100% */

letter-spacing: 0.2px;

color: #0F2336;
}
.description{
    font-family: Roboto;
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 24px;
width: 300px;
color: #576D81;
}
.title-container{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.card{
    width: 400px;
    height: 179px;
    background:#fff;
    display: flex;
    align-items: center;
    justify-content: center;
}
.card-container{
    width: 350px;
    height: 130px;
}
.main{
    width: 100%;
    background: #ebeeee;
    margin-top: 150px;
    border-radius: 15px;
    display: flex;
    align-items: flex-start;
    justify-content: space-around;
}
.icon{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 50px;
    height: 50px;
    border-radius: 7px;
    background: #ebeeee;
}
</style>
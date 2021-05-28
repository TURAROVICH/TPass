<template>
  <div id="app">
        <div class="c0ntainer">
       <Header_tmp/>
       <Welcome/>
       <Cards/>
       <Phone/>
       <About/>
       <Phone1/>
       <Form/>
       </div>
<footer_tmp/>

  </div>
</template>

<script>
import Header_tmp from './components/Header'
import Welcome from './components/welcome'
import Cards from './components/Cards'
import Phone from './components/phone'
import About from './components/about'
import Phone1 from './components/phone-1'
import Form from './components/form'
import footer_tmp from './components/footer'
export default {
  name: 'App',
  components: {
   Header_tmp,
   Welcome,
   Cards,
   Phone,
   About,
   Phone1,
   Form,
   footer_tmp
  }
}
</script>

<style>
/* @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap'); */
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,300;1,900&display=swap');
.c0ntainer{
  width:950px ;
}
#app {
 max-width: 1440px;
 display: flex;
 align-items: center;
 justify-content: center;
 flex-direction: column;
}
*{
  margin:0;
  padding: 0;
  box-sizing: border-box;
  font-family: Roboto;
}
body{
  background: #F5F6F7;
}
</style>

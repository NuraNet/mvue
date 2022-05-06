<template>
  <h1>NuraNet</h1>
  <h2>Accelerate the future.</h2>
 <div class="container">
  <AboutBlock />
 </div>


</template>

<script>

import AboutBlock from './components/AboutBlock.vue'

export default {
  name: 'App',
  components: {AboutBlock}
}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Arima+Madurai:wght@200&family=Cairo:wght@200&family=Goldman&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Baloo+2&display=swap');

h1,p,h2 { 
  font-family: 'Goldman', cursive;
  text-align: center;
}



 .container {
   max-width: 500px;
   margin: 100px auto;
   overflow: auto;
   
   border: 1px solid steelblue;
   padding: 10px;
   border-radius: 5px;
   text-align: left;
  

   font-family: 'Baloo 2', cursive;
   font-size:large;
 }


 .button {
    display: inline-block;
    background: #000;
    color: #fff;
    border: none;
    padding: 10px 20px;
    margin: 5px;
    border-radius: 5px;
    cursor: pointer;
    text-decoration: none;
    font-size: 15px;
    font-family: inherit;


 }


</style>

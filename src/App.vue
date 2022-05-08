<template>
  <div>
 <h1>NuraNet.ai</h1>
<p>Accelerate the future.</p>
  </div>
  <div class="nav"><router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link></div>
  
  <router-view/>

</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Arima+Madurai:wght@200&family=Cairo:wght@200&family=Goldman&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Baloo+2&display=swap');

h1,h2{ 
  font-family: 'Goldman', cursive;
  text-align: center;
  color: black;
  font-size: 2rem;
  margin:1%;

}

.nav {
  text-align: center;
  text-decoration: none;
}

body {
  font-family: 'Baloo 2', cursive;
   font-size:1.2rem;
   text-align: center;
}



 .container {
   max-width: 700px;
   margin: 100px auto;
   overflow: auto;
   
   border: 1px solid steelblue;
   padding: 10px;
   border-radius: 5px;
   box-shadow: 30px 0px 40px rgba(0,0,0,0.1),-30px 0 40px rgba(0,0,0,0.1);
   text-align: left;
  

   font-family: 'Baloo 2', cursive;
   font-size:1.2rem
  
 }


 .button {
    display: inline-block;
    background: #000;
    color: #fff;
    border: none;
    padding: 10px 20px;
    margin: 5px;
    border-radius: 50px;
    cursor: pointer;
    text-decoration: none;
    font-size: 1rem;
    font-family: inherit;
    transition: background 500ms ease;

 }
 .button:hover {
      background: gray;
  }
  
  a:link,a:visited,a:active {
  text-decoration: none;
  color: blue;
  }
  a:hover {
  text-decoration: underline;
  }

</style>

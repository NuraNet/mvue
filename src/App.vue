<template>
  <h1>NuraNet.AI</h1>
  <h2>Accelerate the future.</h2>
 <div class="container">
    <AboutBlock />
  
 </div>

   <div v-if="showBlock">
        <ContactBlock title="Contact Arun"  @close="toggleModal"/>
  </div>

<button class="button" @click="toggleModal">Contact</button>

</template>

<script>

import AboutBlock from './components/AboutBlock.vue'
import ContactBlock from './components/ModalBlock.vue'



export default {
  name: 'App',
  components: {
    AboutBlock,
    ContactBlock
},

    data() {
      return {
      showBlock: false
        }
      },

      methods: {
        toggleModal() {
          this.showBlock = !this.showBlock
        }
      }
}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Arima+Madurai:wght@200&family=Cairo:wght@200&family=Goldman&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Baloo+2&display=swap');

h1,p,h2,body { 
  font-family: 'Goldman', cursive;
  text-align: center;
  color: black;
  font-size: 2rem;
  margin:1%;

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



</style>

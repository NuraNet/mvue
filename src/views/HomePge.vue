<template>
<div class="container">
  <p>Hi 🖐! My name's Arun and welcome to NuraNet!</p>
  <p>The only justification for its existence is to help accelerate the future through training, research, and development.</p>
  My research interests include:
  <ul>
      <li v-for="item in interests" :key="item">
    {{item}}
  </li>
  </ul>
</div>
</template>


<script setup>
//import {reactive} from 'vue'

const interests = [
  "Conversational AI",
  "Brain Computer Interface",
  "Natural Language Processing",
  ]



</script>






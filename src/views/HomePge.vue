<template>
  <div class="container">
Hi 🖐! <br>
My name's Arun George and I created NuraNet as a research and development project.
The only justification for its existence is to help accelerate the future through training, research, and development.
<br><br>
My current research interests include:

<li v-for="i in interests" :key="i">
{{i}}
</li>

</div>
</template>


<script setup>
//import {reactive} from 'vue'

const interests = [
  "CAI",
  "BCI",
  "NLU",
  ]



</script>






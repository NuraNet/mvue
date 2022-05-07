<template>
  <div class="container">
Hi 🖐! <br>
<p>My name's Arun George and I created NuraNet as a research and development project.<br><br>
The only justification for its existence is to help accelerate the future through training, research, and development.
</p>
My current research interests include:

<li v-for="i in interests" :key="i">
{{i}}
</li>

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






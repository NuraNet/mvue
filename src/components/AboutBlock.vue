<template>
Hi 🤚!<br> My name's Arun George and I created <u>NuraNet</u> as a research and development project. <br><br>
The only justification for its existence is to help accelerate the future through technology. <p></p>
My current research interests include:
<ul>
  <li v-for="item in interests" :key="item">{{item}}</li>
</ul>
    
</template>

<script>
export default {
    data() {
        return {
            interests: [
                "Conversational AI",
                "Brain Computer Interface",
                "Natural Language Understanding",
                
            ]
        }

    }
}
</script>
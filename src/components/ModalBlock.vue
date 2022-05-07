<template>

    <div class="backdrop" @click="closeBlock">
         <div class="modal">
         <h1> {{title}}</h1>
         
         </div> 
         
        
  
    </div>
      

</template>


<script> 
    export default {
        props: ['title'],

    methods: {
        closeBlock() {
            this.$emit('close')
         }
        }
    }

</script>

<style scoped>

.modal {
    border-radius: 10px;
    background: white;
    padding: 9px;
   

    max-width: 500px;
   margin: 100px auto;


  
}

.backdrop {
    top:0%;
    position:absolute;
    background: rgba(0,0,0,0.5);
    width: 100%;
    height: 100%;
   


}
</style>


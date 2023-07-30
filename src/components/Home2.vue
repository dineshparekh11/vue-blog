<template>
    <div>
      <h1 >Home components!</h1> 
      <h3>{{ name }}</h3>
      <button>Click here</button>
    </div>
</template>
  
  <script>
  
  export default {
    name: 'HomePages',
    data(){
        return {
            name:'Dinesh'
        }
    }
    };
  </script>

  <style scoped>

  div{
    background-color: rgb(50, 228, 237);
    height : 50px;
  }

  </style>
  
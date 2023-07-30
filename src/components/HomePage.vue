<template>
    <div>
      <h1 >Home components!</h1>  
      <UsersPage />   
      <ProductPage />
      <ProductPage />

    </div>
</template>
  
  <script>
  import UsersPage from './UsersPage';
  import ProductPage from './ProductPage';
  
  export default {
    name: 'HomePage',
    components:{
        UsersPage,
        ProductPage
    }     
    };
  </script>

  <style scoped>

  div{
    background-color: rgb(230, 53, 230);
    height : 50px;
  }

  </style>
  
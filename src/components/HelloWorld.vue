<template>
  <div>
    <div class="con" @click="handleClick"></div>  
    <div class="con1" @click="handleClick"></div> 
  </div>
</template>


<script>
  export default {
    name: 'HelloWorld',
    methods: {
      handleClick () {
        alert(123)
      }
    }
  }
</script>


<style scoped>
  .con{
    width: 100px;
    height: 100px;
    background: red;
  }
  .con1{
    width: 200px;
    height: 200px;
    background: green;
  }
</style>

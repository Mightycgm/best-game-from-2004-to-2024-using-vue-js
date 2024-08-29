<template lang="">
    <div class="navbar">
        <a class="active" href="#">Home</a> 
        <a href="#">Search</a> 
        <a href="#">Contact</a> 
        <a href="#">Login</a>
    </div>

</template>
<script>
export default {
    
}
</script>
<style scoped>
    .navbar {
    width: 100%;
    background-color: #222222;
    overflow: auto;
  }
  
  .navbar a {
    float: left;
    padding: 12px;
    color: white;
    text-decoration: none;
    font-size: 17px;
  }
  
  .navbar a:hover {
    background-color: #000;
  }
  
  .active {
    background-color: #690000;
  }
  .active:hover{
    background-color: #8a0000;
  }
  
  @media screen and (max-width: 500px) {
    .navbar a {
      float: none;
      display: block;
    }
  }
</style>
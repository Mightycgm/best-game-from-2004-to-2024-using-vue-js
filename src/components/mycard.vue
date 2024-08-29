<template lang="">
  <div class="card">
    <img :src="image" alt="Placeholder image" style="width: 100%" />
    <div class="container">
        <h2><b>{{name}}</b></h2>
        <p>{{score}}</p>
        <p class="price">{{price}}</p>
        <p>{{description}}</p>
    </div>
  </div>

</template>
<script>
export default {
    props: ['id', 'name', 'score', 'price', 'description', 'image']
};
</script>
<style scoped>
    h2{
        text-decoration: 5px underline #690000;
    }
    .container{
        padding: 2px 16px;

    }
    .card {
        box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
        transition: 0.3s;
        width: 40%;
        margin: 10px;
        display: inline-block;
    }
    .price{
        color: grey;
    }
</style>

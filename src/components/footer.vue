<template lang="">
    <div class="footer">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Metacritic_logo.svg/1280px-Metacritic_logo.svg.png" alt="Metacritic">
            <div class="info">
                <label>© 2004 - 2024 Games</label><br>
                <label>Source from <a href="https://www.metacritic.com/browse/game/pc/all/all-time/metascore/?releaseYearMin=2004&releaseYearMax=2024&platform=pc&page=1">This</a></label>
            </div>
    </div>
</template>
<script>
export default {

}
</script>
<style scoped>
.footer {
   width: 100%;
   height: 100px;
   background-color: rgba(60, 60, 60, 0.29);
   color: white;
}
.info{
    font-size: 20px;
    padding: 10px;
    text-align: center;

}
.footer a{
    color: white;
    text-decoration: 3px underline #690000;
    font-size: 20px;
}
.footer a:hover{
    color: rgb(216, 216, 216);
    text-decoration: 3px underline #8a0000;
}
.footer img{
    padding: 10px;
    float: left;
    width: 15%;
    height: 100px;
}
</style>
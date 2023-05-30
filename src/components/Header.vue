<script >
import Navbar from './Navbar.vue'
export default{
components : {
    Navbar,
}
}
</script>

<template>
    <div class="container">
        <Navbar />
 
        <img src="../../nightclub/avada-nightclub-homepage-image-200x99.png" alt="">
    <h1>making memories all night long</h1>
    <button>BECOME A VIP</button>
    <img src="../../nightclub/avada-nightclub-play-showreel-200x47.png" alt="">
 </div>





</template>

<style lang="scss" scoped>
.container{
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    gap: 2rem;
    background-image: url(../../nightclub/avada-nightclub-home-hero.jpg);
    background-size: contain;
    
    h1{
        color: white;
    }
    button{

        height: 40px;
        width: 100px;
        background-color: #f63c81;
        border-color:  #f63c81;
        color: white;
        border-radius: 5px;
    }
    img{
        width: 200px;
    }
    
   
}



</style>

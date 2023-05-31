<script>
import { stringifyExpression } from '@vue/compiler-core';


export default{
  props : {
    Image : String,
    title : String,
    description : String
  }
}
</script>

<template>
<div class="container">
    <h4>SPECIAL EVENTS</h4>
    <h1>for your diary</h1>
    <div class="container-image">
        <div class="card" v-for="card in cards" :key="card">
            <img :src="GetImagePath(Image)" alt="">
            <h2>{{ card.title }}</h2>
            <p>{{ card.description }}</p>
        </div>

        <!-- <div class="card">
            <img src="../../nightclub/avada-nightclub-events-2.jpg" alt="">
            <h2>House Nation</h2>
            <p>DJ is the best DJ of this page</p>
        </div>
        <div class="card">
            <img src="../../nightclub/avada-nightclub-events-3.jpg" alt="">
            <h2>Jazz night</h2>
            <p>DJ is the best DJ of this page</p>
        </div>
        <div class="card">
            <img src="../../nightclub/avada-nightclub-events-4-800x450.jpg" alt="">
            <h2>VIP Taster sessions</h2>
            <p>DJ is the best DJ of this page</p>
        </div>
        <div class="card">
            <img src="../../nightclub/avada-nightclub-events-5-1200x675.jpg" alt="">
            <h2>Funky House Rove</h2>
            <p>DJ is the best DJ of this page</p>
        </div>
        <div class="card">
            <img src="../../nightclub/avada-nightclub-events-6-400x225.jpg" alt="">
            <h2>Urban VIbes</h2>
            <p>DJ is the best DJ of this page</p>
        </div> -->

        <button>RSVP NOW</button>
       
    </div>
</div>

</template>

<style lang="scss" scoped>

.container{
        background-image: url(https://www.publicdomainpictures.net/pictures/280000/nahled/dark-blue-glitter-background.jpg);
        
        
        h4{
            text-align: center;
            color: #f03a7e;
            padding-top: 180px;
        }
        h1{
            color:  white;
            text-align: center;
        }
}
.container-image{
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    max-width: 800px;
        margin: auto;
        margin-top: 30px;
    
    .card{
        width: calc(100% / 3 - 2rem);
        color: white;
        img{
            width: 100%;
        }
        h2{
           color: #f03a7e;
        }
    }

    button{
            height: 50px;
            width: 100px;
            background-color:#f63c81;
            border-color:#f63c81;
            border-radius: 5px;
             color: white;
             margin: 50px;
             
            }
}
</style>
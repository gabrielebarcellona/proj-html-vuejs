<script>
export default{
    
}
</script>

<template>
 <div class="container">

       <div class="container-item">
          <h4>WELCOME TO AVADA</h4>
          <h1>  have the night of your life</h1>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos non officiis ipsam quo inventore vitae aspernatur, sint fuga reprehenderit aliquam molestiae quaerat harum culpa. Blanditiis amet quo dolor rerum distinctio. Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim, esse! Delectus dolore nulla harum, exercitationem voluptatibus porro. Mollitia assumenda repellendus earum quidem, accusamus reprehenderit dignissimos, nesciunt ratione nihil distinctio ipsa?</p>

          <div class="container-image">
              <img src="https://media.istockphoto.com/id/627183716/it/foto/folla-concerto.jpg?s=612x612&w=0&k=20&c=hJ1O0WGIANL_9R7w9Sb0Inrg_CXQ0B1V2RE25VnHwQE=" alt="">
              <img src="../../nightclub/avada-nightclub-rooftoplounge-small.jpg" alt="">
              <img src="../../nightclub/avada-nightclub-viplounge-small.jpg" alt="">
              <img src="../../nightclub/avada-nightclub-events-small.jpg" alt="">
           </div>

        </div>

</div>

</template>

<style lang="scss" scoped>  
 .container{
        background-image: url(https://lucidiscoteca.files.wordpress.com/2013/12/1364379217_388623170_5-noleggio-attrezzatura-per-dj-casse-luci-consolle-videoproiettore-fumo-prezzi-bassissimi-sicilia.jpg);
        background-size: contain;
    }
    .container-image{
        display: flex;
        flex-wrap: wrap;
        margin-top: 50px;
        img{
            width:50%
        }
    }
    .container-item{
        padding-top: 150px;
        padding-bottom: 150px;
       text-align: center;
       max-width: 800px;
       margin: auto ;
       color: white;

       h4{
        color: #44aefa;
       }
      
    }
</style>
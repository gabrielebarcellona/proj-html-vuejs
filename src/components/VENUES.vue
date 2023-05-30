<script>
export default{}
</script>

<template>
    <div class="container">
        <h1>VENUES</h1>
       <div class="container-image">
          <h2>rooftop bar</h2>
       </div>
            <div class="container-image">
                <h2>dance lounge</h2>
          </div>
   </div>
</template>


<style lang="scss" scoped>
.container{
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 50px;
    color: white;

    .container-image{
        width: 250px;
        height: 100px;
        background-image: url(../../nightclub/avada-nightclub-rooftoplounge-small.jpg);
        margin-top: 60px;
        background-size: cover;
        h2{
            margin-top: 50px;
        }
    }
}
</style>
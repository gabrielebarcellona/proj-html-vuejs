<script>
export default{

}
</script>

<template>
<div class="container">
    <div class="avada">
        <p>resident dj</p>
        <h1>dj avada</h1>
        <button>VIEW PROFILE</button>
    </div>
    <div class="blondie">
        <p>special guest dj</p>
        <h1>dj blondie</h1>
        <button>VIEW PROFILE</button>
    </div>
   
</div>

</template>

<style lang="scss" scoped>
    .container{
        display: flex;
        height: 400px;
        .avada{
            color: white;
            width: 50%;
            padding: 15px;
            background-image: url(../../nightclub/avada-nightclub-resident-profile.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;

            p{
                opacity: 50%;
            }
            button{
                height: 50px;
                width: 100px;
                background-color: #46b1fd;
                border-color: #46b1fd;
                border-radius: 5px;
                color: white;
            }
        }
        .blondie{
            color: white;
            width: 50%;
            padding: 15px;
            background-image: url(../../nightclub/avada-nightclub-lisahouse-inset-new.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;

            p{
                opacity: 50%;
            }
            button{
                height: 50px;
                width: 100px;
                background-color:#f63c81;
                border-color:#f63c81;
                border-radius: 5px;
                color: white;
            }
        }
    }
</style>
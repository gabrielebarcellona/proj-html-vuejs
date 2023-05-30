<script>
export default {}
</script>

<template>
<div class="container">
    <div>
        <img src="../../nightclub/avada-nightclub-logo-2x.png" alt="">
    </div>
   
    <ul>
        <li>Avada NIghtClub</li>
        <li>100 NIght Club Blvd</li>
        <li>Beverly Hills</li>
        <li><a href="">hl@your-domain.com</a></li>
        <li>+1 (555)000 000</li>
    </ul>
    
</div>

</template>

<style lang="scss" scoped>
    .container{
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
        margin-top: 100px;
        div{
            width: 200px;
            height: 200px;
            img{
                width: 100%;
            }
        }
        ul{
            color: #6c7881;
            list-style: none;
            li{
                padding-top: 30px;
                a{
                    color:#00a4eb;
                    text-decoration: none;
                }
            }
        }
    }
</style>


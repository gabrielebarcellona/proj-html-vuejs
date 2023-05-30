<script>
export default{}
</script>

<template>
    <div class="container">
        <h3>EVENTS</h3>
        <ul>
            <li>
                <img src="../../nightclub/avada-nightclub-events-3-1200x675.jpg" alt="">
                <div>
                 <h1>DJ Fusion</h1>
                 <p>august 19,2022 @ 8:00 am</p>
                </div>
            </li>

            <li>
                <img src="../../nightclub/avada-nightclub-events-5-1200x675.jpg" alt="">
                <div>
                 <h1>DJ Fusion</h1>
                 <p>august 19,2022 @ 8:00 am</p>
                </div>
            </li>

            <li>
                <img src="../../nightclub/avada-nightclub-events-4-66x66.jpg" alt="">
                <div>
                 <h1>DJ Fusion</h1>
                 <p>august 19,2022 @ 8:00 am</p>
                </div>
            </li>

        </ul>
        <p>view All Events</p>
    </div>

</template>

<style lang="scss" scoped>

    .container{
        display: flex;
        flex-direction: column;
        gap: 1rem;
        padding: 20px;
        margin-top: 50px;
        h3{
            color: white;
            text-align: center;
        }
        li{
            
            display: flex;
            div{
                color: #586669;
                h1{
                    color: #30a0fd;
                }
                padding: 15px;
            }
            img{
            width: 100px;
            height: 80px;
        }

        }
        p{
            color: #30a0fd;
        }
       
    }

</style>
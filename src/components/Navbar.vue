<script >
export default{}
</script>

<template>
 <nav>
    <ul>
        <li class="red-parol">HOME</li>
        <li class="parol">THE CLUB</li>
        <li class="parol">EVENTS</li>
        <li><img src="../../nightclub/avada-nightclub-logo.png" alt=""></li>
        <li class="parol">JOBS</li>
        <li class="parol">NEWS</li>
        <li class="parol">CONTACT US</li>
    </ul>

 </nav>
</template>

<style lang="scss" scoped>
     ul{
        display: flex;
        justify-content: center;
        gap: 50px;
        color: white;
        
       
        li{
            list-style: none;
        }
         .parol{
            margin-top: 60px;
         }

        .red-parol{
            color: #cf326c;
            text-decoration: underline;
            margin-top: 60px;
        }
  
     }

     
</style>

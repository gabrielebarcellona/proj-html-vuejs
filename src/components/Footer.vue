<script>
import events from './events.vue'
import NightClub from './NightClub.vue';
import VENUES from './VENUES.vue';
export default {
    components : {
        events , NightClub,VENUES
    }
}

</script>


<template>

<div class="container">
    <div class="second-container">
    <events/>
    <NightClub/>
    <VENUES/>

</div>
    <p>@copyright 2012-2021 | Avado Theme by <span>ThemeFusion</span>|All Rights Reserved | powered by <span>WordPress</span> </p>



</div>

</template>

<style lang="scss" scoped>

.container{
    background-image: url(../../nightclub/avada-nightclub-footer-background-final-2.jpg);
   background-size: contain;
   
 
}

.second-container{
    display: flex;
    max-width: 800px;
    margin: auto;
    gap: 5rem;
   
}
p{
    text-align: center;
    color:#54606a;
}

span{
    color: #6ac0f2;
}
</style>
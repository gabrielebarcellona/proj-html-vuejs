<script>
import first from './first.vue'
import second from './second.vue'
import third from './third.vue'
import fourth from './fourth.vue'
export default{
    data(){
    return {
      cards : [{
        image : "avada-nightclub-events-1.jpg",
        title : "DJ Fusion",
        description : "August 19,2021 @ 8:00 am", 
      }],
      cards : [{
        image : "avada-nightclub-events-2.jpg",
        title : "House Nation",
        description : "August 19,2021 @ 8:00 am", 
      }],
      cards : [{
        image : "avada-nightclub-events-3.jpg",
        title : "Jazz Night",
        description : "August 19,2021 @ 8:00 am", 
      }],
      cards : [{
        image : "avada-nightclub-events-4.jpg",
        title : "VIP Taster Session",
        description : "August 19,2021 @ 8:00 am", 
      }],
      cards : [{
        image : "avada-nightclub-events-5.jpg",
        title : "Funky House Rave",
        description : "August 19,2021 @ 8:00 am", 
      }],
      cards : [{
        image : "avada-nightclub-events-6.jpg",
        title : "Urban Vibes",
        description : "August 19,2021 @ 8:00 am", 
      }],
    }
  },
  methods : {
    GetImagePath : function(img){
      return new URL('../nightclub')
    }
  },
    components:{
        first,second,third,fourth
    }
}
</script>

<template>
   <first/>
   <second/>
   <third/>
   <fourth/>

</template>

<style lang="scss" scoped>

   

</style>
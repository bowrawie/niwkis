<template>
<v-app >
 <v-app-bar
      app
      color="black"
      dark
      elevation="0"
    >
    <img :src="require('./logos/bell.png')" height="20"/>
      

      
      <img  style="margin:auto" :src="require('./logos/mainlogo.png')" height="40"/>
      
      <v-app-bar-nav-icon @click="drawer = true"><img :src="require('./logos/borgir.png')" height="20"/></v-app-bar-nav-icon>
    </v-app-bar>
    <v-main  :color="$vuetify.theme.dark ='Black' ">

   <div class="container mb-0 "  >
    <v-container  fluid class=""
      :color="$vuetify.theme.dark ='Black' "
    >

        <v-card  elevation="0"><img style="margin:auto;   display: block; margin-left: auto; margin-right: auto;width: 100%;height: auto;" :src="require('./logos/posterimage.png')"/>
        
        
        </v-card>
        <div style="margin-top:5%; "><p class="font-weight-light" style="color:yellow; align-items: center;">Hot Games</p></div>   
        <v-card elevation="0" >
           <div class="overflow-x-auto" style="margin:auto;   display: block; margin-left: auto; margin-right: auto;width: 100%;height: auto;">
        <v-card
      class="d-flex justify-center"
      :color="$vuetify.theme.dark ='Black'"
      flat
      tile
    >
      <v-card
        class="overflow-x-auto d-inline d-flex flex-nowrap"
        flat
      >
      <img class=" pa-1" style=" width: 30%;height: auto; flex-wrap: nowrap;" :src="require('./logos/casinogame1.png')"/>
      <img class=" pa-1" style=" width: 30%;height: auto; flex-wrap: nowrap;" :src="require('./logos/casinogame2.png')"/>
      <img class=" pa-1" style=" width: 30%;height: auto; flex-wrap: nowrap;" :src="require('./logos/casinogame3.png')"/>
      <img class=" pa-1" style=" width: 30%;height: auto; flex-wrap: nowrap;" :src="require('./logos/casinogame4.png')"/>
      <img class=" pa-1" style=" width: 30%;height: auto; flex-wrap: nowrap;" :src="require('./logos/casinogame5.png')"/>
      <img class=" pa-1" style=" width: 30%;height: auto; flex-wrap: nowrap;" :src="require('./logos/casinogame6.png')"/>
      <img class=" pa-1" style=" width: 30%;height: auto; flex-wrap: nowrap;" :src="require('./logos/casinogame7.png')"/>
      <img class=" pa-1" style=" width: 30%;height: auto; flex-wrap: nowrap;" :src="require('./logos/casinogame8.png')"/>
      <img class=" pa-1" style=" width: 30%;height: auto; flex-wrap: nowrap;" :src="require('./logos/casinogame9.png')"/>
      <img class=" pa-1" style=" width: 30%;height: auto; flex-wrap: nowrap;" :src="require('./logos/casinogame10.png')"/>
      </v-card>
    </v-card>
            </div>
        </v-card>
    </v-container>

    <v-container  fluid class=" d-inline-flex ma-0 pa-0 "  >
      <div class=" d-inline-flex   " style=" width: 50%; ">
      <img class="pa-2 " style="width: 3rem;height: 3rem; " :src="require('./logos/walleticon.png')"/>
      <div class="d-block-flex  pa-2 " ><h5 class="font-weight-bold" style="margin: auto;">KEN <img style="width: 25%;height: auto;" :src="require('./logos/vipicon.png')"/></h5>
      <div class="d-block-flex  "><p class="font-weight-bold" style="margin: auto;">$ 26,666.08</p></div>
      </div>
      </div>
      <div class="d-inline-flex pa-1  " style=" width: 50%; ">
        <!-- <img class="pa-2 " style="width: 10%;height: auto; " :src="require('./logos/walleticon.png')"/> -->
        <div class="d-block-flex  pa-1 " >
          <p class="font-weight-thin" style="margin: auto; font-size: 10px;"><img style="width: 10%;height: auto;" :src="require('./logos/alerticon.png')"/>
          <br/>DRAGON FESTIVAL IS ON NOW! PRIZE POOL IS $2,000,000
          </p>
        
      </div>

      </div>
    </v-container>

    <v-container  fluid class="d-inline-flex  mb-0 pa-0" >
      
       <div class=" d-block-flex mb-0" style=" width: 20%; white">
        <img class=" d-block mt-2 " style=" width: 100%;height: auto; flex-wrap: nowrap;" :src="require('./logos/usedicon.png')"/>
        <img class=" d-block mt-4" style=" width: 100%;height: auto; flex-wrap: nowrap;" :src="require('./logos/liveicon.png')"/>
        <img class=" d-block mt-4" style=" width: 100%;height: auto; flex-wrap: nowrap;" :src="require('./logos/sporticon.png')"/>
        <img class=" d-block mt-4" style=" width: 100%;height: auto; flex-wrap: nowrap;" :src="require('./logos/lotteryicon.png')"/>
        <img class=" d-block mt-4" style=" width: 100%;height: auto; flex-wrap: nowrap;" :src="require('./logos/pokericon.png')"/>
        <img class=" d-block mt-4" style=" width: 100%;height: auto; flex-wrap: nowrap;" :src="require('./logos/gameicon.png')"/>
    </div>
       <div class="d-block-flex mb-0 " style=" width: 100%;">
        <img class=" d-block ma-1 pa-1 rounded-lg" style=" width: 100%;height: auto;" :src="require('./logos/posterimage1.png')"/>
        <img class=" d-block  ma-1 pa-1 rounded-lg" style=" width: 100%;height: auto; " :src="require('./logos/posterimage2.png')"/>
        <img class=" d-block  ma-1 pa-1 rounded-lg" style=" width: 100%;height: auto;" :src="require('./logos/posterimage3.png')"/>
        <img class=" d-block  ma-1 pa-1 pb-0 mb-0 rounded-lg" style=" width: 100%;height: auto;" :src="require('./logos/posterimage4.png')"/>
    </div>
    </v-container>
    </div>
  </v-main>

      <v-footer 
      app
      color="black"
      black
      >

      <v-btn
        style="margin:auto; background-color: black;"
      >
         <img style="margin:auto" :src="require('./logos/homeicon.png')" height="25"/>
      </v-btn>

      <v-btn
        style="margin:auto; background-color: black;"
      >
         <img style="margin:auto" :src="require('./logos/giftsicon.png')" height="25"/>
      </v-btn>
      <v-btn
        style="margin:auto; background-color: black;"
      >
         <img style="margin:auto" :src="require('./logos/cashicon.png')" height="25"/>
      </v-btn>
      <v-btn
        style="margin:auto; background-color: black;"
      >
         <img style="margin:auto" :src="require('./logos/chaticon.png')" height="25"/>
      </v-btn>
      <v-btn
        style="margin:auto; background-color: black;"
      >
         <img style="margin:auto" :src="require('./logos/profileicon.png')" height="25"/>
      </v-btn>
  </v-footer>
</v-app>
</template>

<script>
  export default {
    data: () => ({
      drawer: false,
      group: null,
      
    }),
    
  }
</script>

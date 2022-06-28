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

   
    <v-container  class="black"
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

    <v-container  class=" d-inline-flex black"  >
      <div class=" d-inline-flex   " style=" width: 50%; ">
      <img class="pa-2 " style="width: 30%;height: auto; " :src="require('./logos/walleticon.png')"/>
      <div class="d-block-flex  pa-2 " ><p class="font-weight-light" style="margin: auto;">KEN <img style="width: 25%;height: auto;" :src="require('./logos/vipicon.png')"/></p>
      <div class="d-block-flex  "><p class="font-weight-light" style="margin: auto;">$ 26,666.08</p></div>
      </div>
      </div>
      <div class="d-inline-flex pa-1  " style=" width: 50%; ">
        <!-- <img class="pa-2 " style="width: 10%;height: auto; " :src="require('./logos/walleticon.png')"/> -->
        <div class="d-block-flex  pa-1 " >
          <p class="font-weight-light" style="margin: auto; font-size: 10px;"><img style="width: 10%;height: auto;" :src="require('./logos/alerticon.png')"/>
          <br/>DRAGON FESTIVAL IS ON NOW! PRIZE POOL IS $2,000,000
          </p>
        
      </div>
      <!-- <div>
        <span style="padding-right:3px; padding-top: 3px; display:inline-block;">
        <img class="" style="width: 30%;height: auto; " :src="require('./logos/alerticon.png')"/></span>
        <p>DRAGON FESTIVAL IS ON NOW! PRIZE POOL IS $2,000,000</p>  
      </div> -->
      </div>
    </v-container>

    <v-container  class="d-inline-flex black" >
      
       <div class=" d-block-flex pa-1 " style=" width: 20%;">
        <img class=" d-block mt-2" style=" width: 100%;height: auto; flex-wrap: nowrap;" :src="require('./logos/usedicon.png')"/>
        <img class=" d-block mt-4" style=" width: 100%;height: auto; flex-wrap: nowrap;" :src="require('./logos/liveicon.png')"/>
        <img class=" d-block mt-4" style=" width: 100%;height: auto; flex-wrap: nowrap;" :src="require('./logos/sporticon.png')"/>
        <img class=" d-block mt-4" style=" width: 100%;height: auto; flex-wrap: nowrap;" :src="require('./logos/lotteryicon.png')"/>
        <img class=" d-block mt-4" style=" width: 100%;height: auto; flex-wrap: nowrap;" :src="require('./logos/pokericon.png')"/>
        <img class=" d-block mt-4" style=" width: 100%;height: auto; flex-wrap: nowrap;" :src="require('./logos/gameicon.png')"/>
    </div>
       <div class="d-block-flex pa-2 " style=" width: 80%;">
        <img class=" d-block pa-1  rounded-lg" style=" width: 100%;height: auto; flex-wrap: nowrap; " :src="require('./logos/posterimage1.png')"/>
        <img class=" d-block pa-1 rounded-lg" style=" width: 100%;height: auto; flex-wrap: nowrap;" :src="require('./logos/posterimage2.png')"/>
        <img class=" d-block pa-1 rounded-lg" style=" width: 100%;height: auto; flex-wrap: nowrap;" :src="require('./logos/posterimage3.png')"/>
        <img class=" d-block pa-1 rounded-lg" style=" width: 100%;height: auto; flex-wrap: nowrap;" :src="require('./logos/posterimage4.png')"/>
    </div>
    </v-container>
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
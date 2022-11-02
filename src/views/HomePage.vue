<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title style="left: -170px;">Home</ion-title>
      </ion-toolbar>
    </ion-header>
    
    <ion-content :fullscreen="true">

      <!-- Card -->
      <ion-grid>
        <ion-row>
          <ion-col>
            <ion-card>
              <ion-card-header>
                <ion-card-subtitle style="color: black;">Kolam</ion-card-subtitle>
                <ion-card-title style="color: black; font-weight: bold;">10</ion-card-title>
              </ion-card-header>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card>
              <ion-card-header>
                <ion-card-subtitle style="color: black;">Kolam Aktif</ion-card-subtitle>
                <ion-card-title style="color: black; font-weight: bold;">8</ion-card-title>
              </ion-card-header>
            </ion-card>
          </ion-col>
        </ion-row>
      </ion-grid>

      <ion-grid>
        <ion-row>
          <ion-col>
            <ion-card>
              <ion-card-header>
                <ion-card-subtitle style="color: black;">Ikan Hidup</ion-card-subtitle>
                <ion-card-title style="color: black;"><span style="font-weight: bold;">182</span> Ekor</ion-card-title>
              </ion-card-header>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card>
              <ion-card-header>
                <ion-card-subtitle style="color: black;">Ikan Mati</ion-card-subtitle>
                <ion-card-title style="color: black;"><span>89</span> Ekor</ion-card-title>
              </ion-card-header>
            </ion-card>
          </ion-col>
        </ion-row>
      </ion-grid>

      <ion-grid>
        <ion-row>
          <ion-col>
            <ion-card>
              <ion-card-header>
                <ion-card-subtitle style="color: black;">Panen 2022</ion-card-subtitle>
                <ion-card-title style="color: black;"><span>109</span> kg</ion-card-title>
              </ion-card-header>
            </ion-card>
          </ion-col>
          <ion-col>
            <ion-card>
              <ion-card-header>
                <ion-card-subtitle style="color: black;">Total Pakan</ion-card-subtitle>
                <ion-card-title style="color: black;"><span>223</span> kg</ion-card-title>
              </ion-card-header>
            </ion-card>
          </ion-col>
        </ion-row>
      </ion-grid>

      <h2 style="margin-left: 10px; margin-top: 10px; margin-bottom: 0;">TOTAL BERAT IKAN</h2>
      
      <!-- slider -->
    <ion-slides>
    <ion-slide>
      <ion-grid>
        <ion-row>
          <ion-col style="width: 100%;">
            <ion-card class="kartu">
        <img alt="Silhouette of mountains" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSpRxOJ_PLPQf1mJfecNMaQ14LQ3pCPABE9Vg&usqp=CAU" />
        <ion-card-header>
          <ion-card-title style="color:black;font-weight: bold;">Lele</ion-card-title>
          <ion-card-subtitle style="color: blue;">200 kg</ion-card-subtitle>
        </ion-card-header>
      </ion-card></ion-col>
          <ion-col>
            <ion-card class="kartu">
        <img alt="Silhouette of mountains" src="https://images-na.ssl-images-amazon.com/images/I/31x71zK0eeL._SX300_QL70_.jpg" />
        <ion-card-header>
          <ion-card-title style="color:black;font-weight: bold;">Nila Merah</ion-card-title>
          <ion-card-subtitle style="color: blue;">200 kg</ion-card-subtitle>
        </ion-card-header>
      </ion-card>
          </ion-col>    
    </ion-row>
    </ion-grid>
    </ion-slide>
    <ion-slide>
      
    </ion-slide>
    <ion-slide>
      <ion-card class="kartu">
        <img alt="Silhouette of mountains" src="https://ionicframework.com/docs/img/demos/card-media.png" />
        <ion-card-header>
          <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
          
          <ion-card-title>Card Title</ion-card-title>
        </ion-card-header>
      </ion-card>
    </ion-slide>
  </ion-slides>

  <h2 style="margin-left: 10px; margin-bottom: 5px; margin-top: 0; ">KUALITAS AIR</h2>

  <ion-slides>
    <ion-slide>
      <ion-grid>
  <ion-row>
    <ion-col>
    
      <ion-card>
        <ion-card-header>
          <ion-card-title style="color: black; right: 50px; bottom: 10px;font-weight: bold;">pH</ion-card-title>
          <ion-card-subtitle style="color: black; right: 12px; bottom: 5px;">Normal<span style="color:blue;"> 6 Kolam</span></ion-card-subtitle>
          <ion-card-subtitle style="color: black; right: 3px; bottom: 5px;">Abnormal<span style="color:blue"> 6 Kolam</span></ion-card-subtitle>
        </ion-card-header>
      </ion-card>
      </ion-col>
      <ion-col>
      <ion-card>
        <ion-card-header>
          <ion-card-title style="color: black; right: 50px; bottom: 10px;font-weight: bold">DO</ion-card-title>
          <ion-card-subtitle style="color: black; right: 12px; bottom: 5px;">Normal<span style="color:blue;"> 6 Kolam</span></ion-card-subtitle>
          <ion-card-subtitle style="color: black; right: 3px; bottom: 5px;">Abnormal<span style="color:blue"> 6 Kolam</span></ion-card-subtitle>
        </ion-card-header>
      </ion-card>
      </ion-col>
    </ion-row>
</ion-grid>
    </ion-slide>
    <ion-slide>
      <h1>Slide 2</h1>
    </ion-slide>
    <ion-slide>
      <h1>Slide 3</h1>
    </ion-slide>
  </ion-slides>

    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonSlides, IonSlide, IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HomePage',
  components: {
    IonContent,
    IonHeader,
    IonPage,
    IonTitle,
    IonToolbar,
    IonSlides, 
    IonSlide
  },
  setup() {
    // Optional parameters to pass to the swiper instance. See https://swiperjs.com/swiper-api for valid options.
    const slideOpts = {
      initialSlide: 1,
      speed: 400
    };
    return { slideOpts }
  }
});
</script>

<style scoped>

img{
  width: 100%;
  height: 100%;
}
span{
  font-weight: bold;
  color: black;
}
.kartu{
  display: flex;
  flex-direction: column;
  width: 100% !important;
  margin: 0 !important;
  margin-left: 50px;
  height: 100%;
}

#container {
  text-align: center;
  
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

ion-card{
    display: flex;
    flex-direction: column;
    width: 100% !important;
    margin: 0 !important;
    background-color: white;
    height: 90%;
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 19px;
  line-height: 22px;
  
  color: #8c8c8c;
  
  margin: 0;
}

#container a {
  text-decoration: none;
}
</style>
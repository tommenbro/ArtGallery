<script setup lang="ts">
  import { IonContent, IonCard, IonCardHeader, IonText, IonCardContent, IonCardTitle, IonCardSubtitle, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';
  import { ref } from 'vue';
  
  const campingSpots = ref([
  {
      id: 0,
      title: "The Golden Man",
      description: "Artwork made for The Order of The Golden Man",
      collection: "Lords and Gods",
      imageURL: "https://i.imgur.com/x89WbOl.png"
    },
    {
      id: 1,
      title: "Alpha Wolf",
      description: "Artwork made for Alpha Labz",
      collection: "Alpha Labz",
      imageURL: "https://i.imgur.com/VKWXnua.png"
    },
    {
      id: 2,
      title: "Baby Bill Murray",
      description: "Artwork for the Baby Bill Murray Inu token.",
      collection: "Bill Murray Inu",
      imageURL: "https://i.imgur.com/GdOC7hn.png"

    },
    {
      id: 3,
      title: "Bill Murray Inu",
      description: "Artwork for the Bill Murray Inu token.",
      collection: "Bill Murray Inu",
      imageURL: "https://i.imgur.com/pJU4BSC.png"

    },
    {
      id: 4,
      title: "Bit Burnin'",
      description: "Artwork for BitBurnReflect.",
      collection: "BitBurnReflect",
      imageURL: "https://i.imgur.com/sT43ewN.png"

    },
    {
      id: 5,
      title: "GoldBoy I",
      description: "Concept Artwork for my upcoming project, GoldBoy.",
      collection: "GoldBoy",
      imageURL: "https://i.imgur.com/spMx8c4.png"

    },
    {
      id: 6,
      title: "GoldBoy II",
      description: "Concept Artwork for my upcoming project, GoldBoy.",
      collection: "GoldBoy",
      imageURL: "https://i.imgur.com/gmjUVSh.png"

    },
    {
      id: 7,
      title: "GoldBoy III",
      description: "Concept Artwork for my upcoming project, GoldBoy.",
      collection: "GoldBoy",
      imageURL: "https://i.imgur.com/5IEAqxJ.png"

    },
    {
      id: 8,
      title: "GoldBoy IV",
      description: "Concept Artwork for my upcoming project, GoldBoy.",
      collection: "GoldBoy",
      imageURL: "https://i.imgur.com/A2gxCJ9.png"

    },
    {
      id: 9,
      title: "GoldBoy V",
      description: "Concept Artwork for my upcoming project, GoldBoy.",
      collection: "GoldBoy",
      imageURL: "https://i.imgur.com/80lStR7.png"

    },
    {
      id: 10,
      title: "GoldBoys",
      description: "Concept Artwork for my upcoming project, GoldBoy.",
      collection: "GoldBoy",
      imageURL: "https://i.imgur.com/UtqkQiW.png"

    },
    {
      id: 11,
      title: "Emma",
      description: "Digital painting, I call her Emma.",
      collection: "Ladies and Goddesses",
      imageURL: "https://i.imgur.com/77gYtbk.png"

    },
    {
      id: 12,
      title: "Eva",
      description: "Digital painting, I call her Eva.",
      collection: "Ladies and Goddesses",
      imageURL: "https://i.imgur.com/wWrEUuP.png"

    },
    {
      id: 13,
      title: "Ella",
      description: "Digital painting, I call her Ella.",
      collection: "Ladies and Goddesses",
      imageURL: "https://i.imgur.com/EzvsQoT.png"

    },
    {
      id: 14,
      title: "How To Make An Ad",
      description: "Digital painting, inspired by the classic sports car ads of the 20th century.",
      collection: "Ladies and Goddesses",
      imageURL: "https://i.imgur.com/hhqB2PQ.png"

    },
    {
      id: 15,
      title: "White Girl Summer",
      description: "Digital painting, mysterious sundress babe transcending space and time.",
      collection: "Ladies and Goddesses",
      imageURL: "https://i.imgur.com/TMJ1guk.png"

    },
    {
      id: 16,
      title: "White Girl Summer II",
      description: "Digital painting, mysterious surfer babe transcending space and time.",
      collection: "Ladies and Goddesses",
      imageURL: "https://i.imgur.com/WEPj9SB.png"

    },
    {
      id: 17,
      title: "Wotan incarnated in modern times",
      description: "Who could it be? ",
      collection: "Lords and Gods",
      imageURL: "https://i.imgur.com/jjmTGjK.png"

    },
    {
      id: 18,
      title: "Twilight of The Gods",
      description: "The final battle?",
      collection: "Ragnarok",
      imageURL: "https://i.imgur.com/uWmD4UH.png"
    },
    {
      id: 19,
      title: "Destroyer of Worlds",
      description: "The great fire",
      collection: "Ragnarok",
      imageURL: "https://i.imgur.com/HXbFRbn.png"

    },
    {
      id: 20,
      title: "Sonic Gold I",
      description: "Concept artwork for the Sonic Gold token",
      collection: "Sonic Gold",
      imageURL: "https://i.imgur.com/8hdfQ6L.png"

    },
    {
      id: 21,
      title: "Sonic Gold II",
      description: "Concept artwork for the Sonic Gold token",
      collection: "Sonic Gold",
      imageURL: "https://i.imgur.com/8gm5nk9.png"

    },
    {
      id: 22,
      title: "Sonic Gold III",
      description: "Concept artwork for the Sonic Gold token",
      collection: "Sonic Gold",
      imageURL: "https://i.imgur.com/v8UKJ43.png"

    },
    {
      id: 23,
      title: "Sonic Gold IV",
      description: "Concept artwork for the Sonic Gold token",
      collection: "Sonic Gold",
      imageURL: "https://i.imgur.com/h1VLzRg.png"

    },
    {
      id: 24,
      title: "The Upkeeper",
      description: "A spanish upkeeper enjoying the view of his work",
      collection: "The Walks of Life",
      imageURL: "https://i.imgur.com/nbCB23S.png"

    },
    {
      id: 25,
      title: "MagiAto",
      description: "The goodest wizard of them all.",
      collection: "Divine Inspirations",
      imageURL: "https://i.imgur.com/KybMviL.png"

    },
  ]) 
  </script>

<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Digital Art By Aryes</ion-title>
        
      </ion-toolbar>
    </ion-header>
    
    <ion-content :fullscreen="true">

      <ion-card v-for="spot in campingSpots" :key="spot.id">
        <img :src="spot.imageURL" />
        <ion-card-header>
        <ion-card-subtitle>
          {{spot.collection}}
        </ion-card-subtitle>
        <ion-card-title>{{spot.title}}</ion-card-title>
      </ion-card-header>

      <ion-card-content>
        {{spot.description}}
      </ion-card-content>
      </ion-card>
      
    </ion-content>
  </ion-page>
</template>

<style scoped>
#container {
  text-align: center;
  
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  
  
  color: #8c8c8c;
  
  margin: 0;
}

#container a {
  text-decoration: none;
}
</style>

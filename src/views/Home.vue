<template>
  <ion-page>
    <!-- <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Blank</ion-title>
      </ion-toolbar>
    </ion-header> -->
    
    <ion-content :fullscreen="true">
      <ion-searchbar 
      animated placeholder="search song" 
      show-cancel-button="focus">
      </ion-searchbar>
     <app-buttons></app-buttons>
      <ion-button expand="block" fill="outline">Open Song</ion-button>   
    </ion-content>
  </ion-page>
</template>

<script>
import { IonContent, IonPage,  IonSearchbar, IonButton } from '@ionic/vue';
import AppButtons from '../component/AppButtons.vue'
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'Home',
  components: {
    IonContent,
    IonPage,
    IonSearchbar,
    AppButtons,
    IonButton
  }
});
</script>

<style >

</style>
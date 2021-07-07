<template>
<ion-page>
  <!-- <ion-app> -->
  <ion-header>
    <ion-toolbar>
      <ion-searchbar placeholder="search hymn"></ion-searchbar>
    </ion-toolbar>
  </ion-header>

  <ion-content >
    <ButtonTab />
    <OpenHymn />
  </ion-content>

</ion-page>
</template>

<script>
import ButtonTab from './component/ButtonTab.vue'
import OpenHymn from './component/OpenHymn.vue'
import { IonHeader, IonToolbar, IonPage, IonSearchbar} from '@ionic/vue'
export default {
  name: 'App',
  components: {

    IonHeader,
    IonToolbar,
    ButtonTab,
    OpenHymn,
    IonPage,
    IonSearchbar
  }


}
</script>

<style>

</style>
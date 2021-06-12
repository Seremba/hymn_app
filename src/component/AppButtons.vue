<template>
  <ion-grid>
      <ion-row>
          <ion-col size="3">
             1
          </ion-col>
          <ion-col size="3">
             2
          </ion-col>
          <ion-col size="3">
             3
          </ion-col>
      </ion-row>
      <ion-row>
          <ion-col size="3">
             4
          </ion-col>
          <ion-col size="3">
             5
          </ion-col>
          <ion-col size="3">
             6
          </ion-col>
      </ion-row>
      <ion-row>
          <ion-col size="3">
             7
          </ion-col>
          <ion-col size="3">
             8
          </ion-col>
          <ion-col size="3">
             9
          </ion-col>
      </ion-row>
      <ion-row>
          <ion-col size="3">
             icon
          </ion-col>
          <ion-col size="3">
             0
          </ion-col>
          <ion-col size="3">
             icon
          </ion-col>
      </ion-row>
  </ion-grid>
</template>

<script>
import { IonGrid, IonRow, IonCol } from '@ionic/vue'
import { defineComponent } from 'vue';
export default defineComponent ({
 components: {
     IonGrid, IonRow, IonCol
 }
})
</script>

<style>

</style>
<template>
   <ion-grid>
         <ion-row>
            <ion-col >
               <div>
                1
               </div>
            </ion-col>
            <ion-col>
               <div>
                 2
               </div>
            </ion-col>
            <ion-col>
               <div>
               3
               </div>
            </ion-col>
         </ion-row>
         <!-- another row  -->
         <ion-row >
            <ion-col>
               <div>
                4
               </div>
            </ion-col>
            <ion-col>
               <div>
               5
               </div>
            </ion-col>
            <ion-col>
               <div>
               6
               </div>
            </ion-col>
         </ion-row>
         <ion-row >
            <ion-col>
               <div>
                7
               </div>
            </ion-col>
            <ion-col>
               <div>
               8
               </div>
            </ion-col>
            <ion-col>
               <div>
               9
               </div>
            </ion-col>
         </ion-row>
         <!-- last row  -->
         <ion-row >
            <ion-col>
               <div >
                    <ion-icon :icon="heart"></ion-icon>
               </div>
            </ion-col>
            <ion-col>
               <div>
                0
               </div>
            </ion-col>
            <ion-col>
               <div>
                    <ion-icon :icon="trash"></ion-icon>
               </div>
            </ion-col>
         </ion-row>
         </ion-grid>   
</template>

<script>
import { IonGrid, IonRow, IonCol, IonIcon } from '@ionic/vue'
import { defineComponent } from 'vue';
import { heart, trash } from 'ionicons/icons'
export default defineComponent ({
 components: {
     IonGrid, IonRow, IonCol, IonIcon
 },
 data(){
    return {
       heart, trash 
    }
 }
})
</script>

<style >
ion-grid {
   padding-top: 70%;
}
ion-col {
  text-align: center;
  margin: 0;
  padding: 0px;
  min-height: 100%;
}
ion-col div {
  margin: auto;
  color: white;
  cursor: pointer;
  padding: 1.8rem;
  font-size: 1.8rem;
  background: rgb(151, 145, 140);
  border: 1px solid white;
}


</style>
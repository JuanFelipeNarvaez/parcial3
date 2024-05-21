<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Probando</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content :fullscreen="true">
      <a href="carro">carro</a>
      <a href="categoria">categoria</a>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';
</script>

<style scoped>
#login-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100%;
}

#cart-image {
  margin-bottom: 20px;
  width: 100px;
}

#description {
  margin-bottom: 20px;
  text-align: center;
}

#description p {
  margin: 0;
  padding: 10px; 
}

#login-form {
  max-width: 300px;
  width: 100%;
}
</style>
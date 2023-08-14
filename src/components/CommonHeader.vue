<template>
  <v-app-bar :elevation="1" color="#F5F5F5">
    <v-img
      max-width="64"
      aspect-ratio="1/1"
      contain
      src="../assets/logo.png"
      alt="Logo"
    ></v-img>
    <v-app-bar-title>
      Морские Гидравлические Системы
    </v-app-bar-title>
    <v-btn text to="/">Главная</v-btn>
    <v-btn text to="/services">Услуги</v-btn>
    <v-btn text to="/contacts">Контакты</v-btn>
  </v-app-bar>
</template>

<script>
export default {
  name: 'CommonHeader'
}
</script>

<style>
</style>

<template>
  <v-main>
    <v-container class="d-flex flex-column align-center">
      <v-text-h2 class="font-weight-bold" style="font-size: 24px;">Морские Гидравлические Системы</v-text-h2>
      <v-spacer class="mt-2"></v-spacer>
      <v-paragraph class="mt-2">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis dolores iure sapiente odit minus doloremque dignissimos consequatur possimus vel ea. Quo, hic? A, fugiat molestias quos consequatur ut aliquam odit.
      </v-paragraph>
      <v-spacer></v-spacer>
      <v-paragraph class="mt-2">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis dolores iure sapiente odit minus doloremque dignissimos consequatur possimus vel ea. Quo, hic? A, fugiat molestias quos consequatur ut aliquam odit.
      </v-paragraph>
      <v-spacer></v-spacer>
      <v-paragraph class="mt-2">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis dolores iure sapiente odit minus doloremque dignissimos consequatur possimus vel ea. Quo, hic? A, fugiat molestias quos consequatur ut aliquam odit.
      </v-paragraph>
      <v-spacer></v-spacer>
      <v-paragraph class="mt-2">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis dolores iure sapiente odit minus doloremque dignissimos consequatur possimus vel ea. Quo, hic? A, fugiat molestias quos consequatur ut aliquam odit.
      </v-paragraph>
      <v-spacer></v-spacer>
      <v-paragraph class="mt-2">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis dolores iure sapiente odit minus doloremque dignissimos consequatur possimus vel ea. Quo, hic? A, fugiat molestias quos consequatur ut aliquam odit.
      </v-paragraph>
      <v-spacer></v-spacer>
      <v-paragraph class="mt-2">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis dolores iure sapiente odit minus doloremque dignissimos consequatur possimus vel ea. Quo, hic? A, fugiat molestias quos consequatur ut aliquam odit.
      </v-paragraph>
    </v-container>
    <v-row class="flex-0-1 flex-column align-center justify-center mt-10">
      <v-img
        :width="1530"
        aspect-ratio="16/9"
        contain
        src="../assets/example-image.jpg"
        class="rounded"
      ></v-img>
      <v-row
        class="flex-0-1 flex-row align-center justify-center mt-5 mb-10"
      >
        <v-img
          :width="755"
          aspect-ratio="16/9"
          contain
          src="../assets/example-image.jpg"
          class="rounded mr-6"
        ></v-img>
        <v-img
          :width="755"
          aspect-ratio="16/9"
          contain
          src="../assets/example-image.jpg"
          class="rounded"
        ></v-img>
      </v-row>
    </v-row>
  </v-main>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'HomeView'
})
</script>

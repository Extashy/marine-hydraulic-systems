<template>
  <v-footer class="flex-0-1 align-center flex-column" color="#F5F5F5" border>
    <div>
      &#169; 2023 Морские Гидравлические Системы
    </div>
    <v-btn href="tel:+7-988-668-40-40" variant="text" class="pa-0 ma-0">
      +7 988 668 40 40
    </v-btn>
    <v-btn href="tel:+7-918-046-13-27" variant="text" class="pa-0 ma-0">
      +7 918 046 13 27
    </v-btn>
    <v-btn @click="sendEmail" variant="text" class="text-lowercase pa-0 ma-0">
      mgsystems@inbox.ru
    </v-btn>
  </v-footer>
</template>

<script>
export default {
  name: 'CommonFooter',
  methods: {
    sendEmail () {
      window.location.href = 'mailto:mgsystems@inbox.ru'
    }
  }
}
</script>

<style>
</style>

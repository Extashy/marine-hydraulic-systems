<template>
  <v-main>
    <v-container class="d-flex flex-column align-center">
      <v-text-h2 class="font-weight-bold mb-3" style="font-size: 32px;">
        Наши контакты
      </v-text-h2>
      <v-sheet class="pa-6 mb-4" :elevation="2" border>
        <v-text class="font-weight-bold" style="font-size: 18px;">ООО "Морские Гидравлические Системы"</v-text>
        <v-spacer class="mt-6"></v-spacer>
        <v-text class="font-weight-bold">Юридический адрес:</v-text>
        <v-spacer></v-spacer>
        <v-text>353993 Краснодарский край г. Новороссийск с. Мысхако ул. Заветная 64/4</v-text>
        <v-spacer class="mt-4"></v-spacer>
        <v-text class="font-weight-bold">Фактический адрес:</v-text>
        <v-spacer></v-spacer>
        <v-text>353919 Краснодарский край г. Новороссийск ул. Пархоменко д. 45</v-text>
        <v-spacer class="mt-4"></v-spacer>
        <v-text class="font-weight-bold">E-mail:</v-text>
        <v-spacer></v-spacer>
        <v-btn @click="sendEmail" variant="text" class="text-lowercase pa-0 ma-0">
          mgsystems@inbox.ru
        </v-btn>
        <v-spacer class="mt-4"></v-spacer>
        <v-text class="font-weight-bold">Телефон:</v-text>
        <v-spacer></v-spacer>
        <v-btn href="tel:+7-988-668-40-40" variant="text" class="pa-0 ma-0">
          +7 988 668 40 40
        </v-btn>
        <v-spacer></v-spacer>
        <v-btn href="tel:+7-918-046-13-27" variant="text" class="pa-0 ma-0">
          +7 918 046 13 27
        </v-btn>
      </v-sheet>
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1417.8257500899697!2d37.78121757313343!3d44.70631355372339!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x40f1f9030f1d3db1%3A0xf60a1e4a5d2bb9ce!2z0YPQuy4g0J_QsNGA0YXQvtC80LXQvdC60L4sIDQ1LCDQndC-0LLQvtGA0L7RgdGB0LjQudGB0LosINCa0YDQsNGB0L3QvtC00LDRgNGB0LrQuNC5INC60YDQsNC5LCAzNTM5MDU!5e0!3m2!1sru!2sru!4v1691420627644!5m2!1sru!2sru"
        width="600"
        height="450"
        style="border:0;"
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade"
      ></iframe>
    </v-container>
  </v-main>
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

<template>
  <v-app>
    <CommonHeader />
    <v-main>
      <router-view/>
    </v-main>
    <CommonFooter />
  </v-app>
</template>

<script>
import CommonHeader from './components/CommonHeader.vue'
import CommonFooter from './components/CommonFooter.vue'

export default {
  name: 'App',
  components: {
    CommonHeader,
    CommonFooter
  },
  data: () => ({
    //
  })
}
</script>

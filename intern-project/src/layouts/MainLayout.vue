<template>
  <q-layout view="hHh Lpr lff">
    <q-page-container>
      <keep-alive>
        <router-view />
      </keep-alive>
    </q-page-container>
  </q-layout>
</template>

<script>
import { date } from 'quasar'


export default {
  name: 'MainLayout',
  data () {
    return {
      leftDrawerOpen: false,
    }
  },
  computed: {
    todaysDate(){
      let timeStamp=Date.now()
      return date.formatDate(timeStamp, 'dddd D MMMMM');
    } 
  }
}
</script>

<template>
  <v-app dark>
    
    <v-app-bar
      :clipped-left="clipped"
      fixed
      app
    >
      <v-spacer />
        <img src="https://i.imgur.com/uajqPx8.png" style="height: 55px;" alt="">
      <v-spacer />
      
    </v-app-bar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>

    <v-footer
      :fixed="fixed"
      app
    >
      <span>&copy; 2019</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Mysteries Of Existence'
    }
  }
}
</script>

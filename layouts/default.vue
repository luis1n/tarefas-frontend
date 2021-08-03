<template>
  <v-app>
    <v-main>
      <v-container>
        <app-menu/>
        <nuxt />
      </v-container>
    </v-main>
    <v-footer>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  components: {
    AppMenu: () => import('../components/AppMenu')
  }
}
</script>

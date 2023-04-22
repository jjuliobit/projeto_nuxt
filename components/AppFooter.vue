<template>
  <v-footer color="primary lighten-1" padless>
    <v-row justify="center" no-gutters>
      <v-btn v-for="link in links" :key="link.id" text rounded class="my-2">
        {{ link.name }}
      </v-btn>
      <v-col class="primary lighten-2 py-4 text-center white--text" cols="12">
        {{ new Date().getFullYear() }} — <strong>Julio</strong>
      </v-col>
    </v-row>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    links: [
      { id: 1, name: 'Home' },
      { id: 2, name: 'About Us' },
      { id: 3, name: 'Team' },
      { id: 4, name: 'Services' },
      { id: 5, name: 'Blog' },
      { id: 6, name: 'Contact Us' },
    ],
  }),
}
</script>
<template>
  <nav>
    <v-toolbar flat app>
        <v-app-bar-nav-icon class="grey--text" @click="drawer = !drawer"></v-app-bar-nav-icon>
      <v-toolbar-title class="text-uppercase grey--text">
        <span class="font-weight-light">Kyles</span>
        <span>Dev</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
    </v-toolbar>
    <v-navigation-drawer v-model="drawer" temporary app class="indigo">
          <p>test</p>
</v-navigation-drawer>
  </nav>
</template>

<script>
export default {
    data() {
        return {
            drawer: false
        }
    }
};
</script>

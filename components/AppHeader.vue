<template>
    <div>
        <v-navigation-drawer v-model="drawer" clipped :fixed="$vuetify.breakpoint.mdAndDown" app>
        </v-navigation-drawer>
        <v-app-bar clipped-left app :fixed="true">
            <v-app-bar-nav-icon v-if="$vuetify.breakpoint.mdAndDown" @click="drawer = !drawer"></v-app-bar-nav-icon>
            <v-toolbar-title class="headline text-uppercase">
                <span>Logo</span>
            </v-toolbar-title>
            <v-spacer></v-spacer>
            <v-menu left bottom>
                <template v-slot:activator="{ on }">
                    <v-btn icon v-on="on">
                       <MenuIcon />
                    </v-btn>
                </template>
                <v-list>
                    <v-list-item @click="$vuetify.theme.dark = !$vuetify.theme.dark" v-model="success">
                        <v-list-item-title>Dark Mode</v-list-item-title>
                        <mdicon name="react" />
                    </v-list-item>
                </v-list>
            </v-menu>
        </v-app-bar>
    </div>
</template>
<script>
import MenuIcon from 'vue-material-design-icons/Menu.vue';
export default {
    name: "Default",
    data: () => ({
        drawer: null,
        success: null
    }),
    components: {
        MenuIcon,
    }
}
</script>

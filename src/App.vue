<template>
       <v-app id="app" light standalone >
        <v-toolbar fixed light>
            <v-toolbar-title class="">The Feeling detection</v-toolbar-title>
        </v-toolbar>
        <main>
            <v-container fluid>
               <router-view></router-view>
            </v-container>
        </main>

    </v-app>
</template>

<script>
export default {

}
</script>

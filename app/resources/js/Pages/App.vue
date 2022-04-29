<template>
    <v-app>
        <Navbar></Navbar>
        <v-navigation-drawer color="grey-darken-2" permanent></v-navigation-drawer>
        <v-main>
            <v-card>
                <v-card-title>
                    <h1>Dupa</h1>
                </v-card-title>
                <v-card-content>
                    <h1>Dupa</h1>
                </v-card-content>
            </v-card>
        </v-main>
    </v-app>
</template>

<style>

</style>

<script>
import Navbar from "../components/Navbar";

export default {
    components: {Navbar}
}
</script>

<template>
    <v-app-bar class="bar-nav">
        <v-container>
            <v-row>
                <v-col auto>
                    <v-btn id="btn-nav" large rounded>
                        <span>Video</span>
                    </v-btn>
                </v-col>
                <v-col auto>
                    <v-btn id="btn-nav"  large rounded>
                        <span>Music</span>
                    </v-btn>
                </v-col>
                <v-col auto>
                    <v-btn id="btn-nav"  large rounded>
                        <span>Book</span>
                    </v-btn>
                </v-col>
                <v-col auto>

                    <v-btn class="btn-nav"  large rounded>
                        <span>Image</span>
                    </v-btn>
                </v-col>
            </v-row>
        </v-container>
    </v-app-bar>
</template>


<style lang="scss">
@import '../assets/styles/header.scss';


</style>
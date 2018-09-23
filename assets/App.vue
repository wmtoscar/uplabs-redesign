<template>
    <v-app light>
        <header id="webViewHeader" class="clearfix  hidden-sm-and-down">
            <div class="uplabs-header">
                <div>
                    <v-btn
                            icon
                            @click.stop="mini = !mini"
                    >
                        <i class="material-icons">menu</i>
                    </v-btn>
                </div>
                <div class="logo-wrapper">
                    <a href="javascript:void(0)">
                        <img src="https://www.uplabs.com/logos/uplabs/default--color.svg" class="logo">
                    </a>
                </div>
                <div class="search-wrapper">
                    <v-text-field
                            class="mx-5 searchbox"
                            flat
                            label="Search for UI Examples, Download and More"
                            prepend-inner-icon="search"
                            solo-inverted
                            type="search"
                    ></v-text-field>
                </div>
                <div class="profile-notification ml-auto">
                    <a href="javascript:void(0)" class="d-block menu-icons">
                        <i class="material-icons">notifications</i>
                    </a>
                    <a href="javascript:void(0)" class="d-block">
                        <div class="avatar-wrapper">
                            <img
                                    src="https://lh4.googleusercontent.com/-AuQHOhrp8h8/AAAAAAAAAAI/AAAAAAAABIk/fYVaNcUXfLg/photo.jpg">
                        </div>
                    </a>
                </div>
            </div>
        </header>
        <v-navigation-drawer
                :mini-variant.sync="mini"
                v-model="drawer"
                hide-overlay
                stateless
        >

        <v-list class="pt-0" dense>
            <v-divider></v-divider>

            <v-list-tile
                    v-for="item in items"
                    :key="item.title"
                    @click=""
            >
                <v-list-tile-action>
                    <v-icon>{{ item.icon }}</v-icon>
                </v-list-tile-action>

                <v-list-tile-content>
                    <v-list-tile-title>{{ item.title }}</v-list-tile-title>
                </v-list-tile-content>
            </v-list-tile>
        </v-list>
        </v-navigation-drawer>
    </v-app>
</template>
<style lang="sass">
    @import './scss/app'
</style>
<script>
    export default {
        data () {
            return {
                drawer: true,
                items: [
                    { title: 'Home', icon: 'dashboard' },
                    { title: 'About', icon: 'question_answer' }
                ],
                mini: true,
                right: null
            }
        }
    }
</script>

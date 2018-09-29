<template>
    <v-app light>
        <header id="webViewHeader" class="clearfix  hidden-sm-and-down header-basic">
            <div class="uplabs-header">
                <div>
                    <v-btn
                            icon
                            @click.stop="mini = !mini"
                            @click="toggleDrawer()"
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
        <div class="content">
            <v-navigation-drawer
                    :mini-variant.sync="mini"
                    v-model="drawer"
                    hide-overlay
                    stateless
                    class="d-inline-block uplabs-nav"
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
                <v-divider></v-divider>
                <v-list class="pt-0" dense>
                    <v-divider></v-divider>

                    <v-list-tile
                            v-for="item in items2"
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
                    <v-divider></v-divider>
                    <v-list-tile
                            v-for="item in items3"
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
            <div class="main-container" v-bind:class="{isOpened: isOpenedClass}">
                <router-view></router-view>
            </div>
        </div>
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
                isOpenedClass:false,
                items: [
                    { title: 'Home', icon: 'home' },
                    { title: 'Collection', icon: 'group_work' },
                    { title: 'Inspiration', icon: 'pages' },
                    { title: 'Market', icon: 'store' },
                ],
                items2: [
                    { title: 'Android', icon: 'android' },
                    { title: 'iOS', icon: 'phone_iphone' },
                    { title: 'Web', icon: 'personal_video' },
                    { title: '3D', icon: 'invert_colors' },
                ],
                items3: [
                    { title: 'Chat', icon: 'chat' },
                    { title: 'About', icon: 'account_balance' },
                    { title: 'Terms', icon: 'info' },
                    { title: 'FAQ', icon: 'live_help' },
                ],
                mini: true,
                right: null
            }
        },
        methods: {
            toggleDrawer: function () {
                return {
                    isOpened: !this.isOpenedClass
                };
            }
        }
    }
</script>

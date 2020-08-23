<template>
<header class="header_main d-flex px-3 align-center">
    <div class="brand__logo">
        <div class="d-flex">
            <v-icon color="white">home</v-icon>
            <h3 style="color: white">Logo</h3>
        </div>
    </div>
    <v-app-bar-nav-icon class="toolbar__icon white--text" @click="navShow"></v-app-bar-nav-icon>
    <transition name="slide">
        <div class="navbar__main" v-if="nav">
            <div class="nav__bar_left ml-lg-2">
                <ul class="nab__bar">
                    <li class="active">
                        <a href="#">
                            <v-icon color="white">format_list_bulleted</v-icon> Reports
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <v-icon color="white">map</v-icon> Map
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <v-icon color="white">addchart</v-icon> Gallery
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <v-icon color="white">directions_off</v-icon> Statistics
                        </a>
                    </li>
                </ul>
            </div>
            <div class="nav__bar_left">
                <ul class="nab__bar">
                    <li>
                        <a href="#">
                            <v-icon color="white">info</v-icon> Tutorials
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <v-icon color="white">settings</v-icon> Settings
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <v-icon color="white">power_settings_new</v-icon> Log Out
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </transition>
    <div class="navbar__main nav_desktop">
        <div class="nav__bar_left ml-lg-2">
            <ul class="nab__bar">
                <li class="active">
                    <a href="#">
                        <v-icon color="white">format_list_bulleted</v-icon> Reports
                    </a>
                </li>
                <li>
                    <a href="#">
                        <v-icon color="white">map</v-icon> Map
                    </a>
                </li>
                <li>
                    <a href="#">
                        <v-icon color="white">addchart</v-icon> Gallery
                    </a>
                </li>
                <li>
                    <a href="#">
                        <v-icon color="white">directions_off</v-icon> Statistics
                    </a>
                </li>
            </ul>
        </div>
        <div class="nav__bar_left">
            <ul class="nab__bar">
                <li>
                    <a href="#">
                        <v-icon color="white">info</v-icon> Tutorials
                    </a>
                </li>
                <li>
                    <a href="#">
                        <v-icon color="white">settings</v-icon> Settings
                    </a>
                </li>
                <li>
                    <a href="#">
                        <v-icon color="white">power_settings_new</v-icon> Log Out
                    </a>
                </li>
            </ul>
        </div>
    </div>
</header>
</template>

<script>
export default {
    data() {
        return {
            nav: false
        }
    },
    methods: {
        navShow() {
            this.nav = !this.nav
        }
    }
}
</script>

<style lang="scss">
.header_main {
    background: #102c42;
    position: relative;
    height: 45px;

    .nab__bar {
        .v-icon {
            margin-right: 10px;
            font-size: 24px;
        }
    }
}

.nab__bar {
    list-style-type: none;
    display: flex;
    margin: 0;
    padding: 0;

    li {

        a {
            text-decoration: none;
            padding: 10px 15px;
            display: inline-block;
            color: white;
        }

    }

    .active {
        position: relative;

        &::before {
            content: "";
            position: absolute;
            width: 100%;
            height: 4px;
            background: rgb(231, 231, 231);
            bottom: 0;
        }
    }
}

.nab__bar li a:not(.active):hover {
    background: #3e4d68c9;
}

.toolbar__icon {
    display: none;
}

.navbar__main {
    width: 100%;
    display: flex;
    justify-content: space-between;
}

.nav_desktop {
    display: flex;
}
</style>

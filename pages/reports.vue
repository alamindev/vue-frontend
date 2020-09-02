<template>
<div>
    <ReportNav />

    <div v-for="report in allreports" v-bind:key="report.id" class="filter__content_main d-flex flex-md-row flex-column align-center align-md-stretch">
        <div class="filter__content_left d-sm-flex">
            <div class="content_image">
                <v-img height="250" aspect-ratio="1" :src="report.main_img"></v-img>
                <div class="photo__view">
                    <v-icon>photo</v-icon> 1+ Photo
                </div>
            </div>
            <div class="map_image">
                <v-img height="250" aspect-ratio="1" :src="'/'+report.map_img"></v-img>
            </div>
        </div>
        <div class="filter__content_right">
            <div class="d-flex justify-space-between">
                <div class="content_left">
                    <ul>
                        <li v-for="(list, index) in report.lists" :key="index">
                            <v-icon>{{ list.icon }}</v-icon> {{ list.text }}
                        </li>
                    </ul>
                </div>
                <div class="content_right">
                    <div class="mb-2 d-flex flex-no-wrap align-center">
                        {{ $t('report.id') }}: <span class="content__id ml-1">{{ report.id }}</span>

                    </div>
                    <div class="edit__icon">
                        <v-icon>edit </v-icon>
                    </div>
                </div>
            </div>
            <div class="button__area">
                <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                    <v-icon>remove_red_eye </v-icon> {{ $t('report.see_details') }}
                </v-btn>
                <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                    <v-icon>location_on </v-icon>{{ $t('report.show_map') }}
                </v-btn>
                <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                    <v-icon>mail_outline </v-icon> {{ $t('report.send_email') }}
                </v-btn>
                <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                    <v-icon>chat_bubble_outline </v-icon> {{ $t('report.comments') }}
                </v-btn>
                <v-btn class="mx-1 my-1 px-2   text-capitalize" outlined>
                    <v-icon>accessibility_new </v-icon> {{ $t('report.street_view') }}
                </v-btn>
            </div>
        </div>

    </div>

</div>
</template>

<script>
import ReportNav from '~/components/ReportNav.vue'
import {
    mapGetters
} from 'vuex';

export default {
    nuxtI18n: {
        paths: {
            en: '/reports',
            fr: '/rapports',
        }
    },
    components: {
        ReportNav,
    },
    computed: {
        ...mapGetters({
            allreports: 'reports/allreports'
        })
    }
}
</script>

<style lang="scss">
.filter__content_main {
    border-bottom: 1px solid #aaaaaa;
}

.content_left {
    padding-left: 10px;
    padding-top: 10px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100%;

    ul {
        list-style: none;
        padding: 0;
        color: #808080 !important;
        padding-bottom: 2px;
        font-size: 15px;

        li {
            .v-icon {
                font-size: 18px
            }

            font-size: 14px;

            .theme--light.v-icon {
                color: #acacac;
            }
        }
    }
}

.content_image {
    width: 240px;

}

.map_image {
    width: 240px;
}

.content__id {
    background: #aaa;
    border-radius: 50px;
    padding: 5px 10px;
    color: white;
}

.filter__content_main:hover .filter__content_right {
    background: #ebebeb;
}

.edit__icon {
    background: #aaa;
    border-radius: 50px;
    padding: 5px 10px;
    display: inline-block;

    .v-icon {
        color: white;
        font-size: 18px;
    }
}

.content_right {
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    padding: 15px;
}

.filter__content_right {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.button__area {
    display: flex;
    flex-wrap: wrap;
    margin-left: 8px;

    button {
        font-size: 14px;

        .v-icon {
            font-size: 18px;
            margin-right: 5px;
        }
    }
}

.button__area button {
    background: white;
    border: 1px solid #ccc;

    &:hover {
        color: #333;
        background-color: #ebebeb;
        border-color: #adadad;
    }
}

.content_image {
    position: relative;

    .photo__view {
        position: absolute;
        width: 100%;
        height: 42px;
        background: #102c42;
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        bottom: 0;
        font-size: 14px;

        .v-icon {
            color: white;
            font-size: 26px;
            margin-right: 5px;
        }
    }
}
</style>

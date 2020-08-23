<template>
<div class="d-flex flex-column flex-md-row  align-center justify-md-space-between second__nav">
    <div class="nav__left_side d-flex align-center flex-wrap  justify-center">
        <v-btn class="mx-1 my-2 px-2 font-weight-black   text-capitalize" outlined color="grey lighten-3" @click="filterShow">
            <v-icon v-if="filter">
                keyboard_arrow_up
            </v-icon>
            <v-icon v-if="!filter">
                keyboard_arrow_down
            </v-icon>
            Filter is active
        </v-btn>
        <v-btn class="mx-1 my-2 px-2 font-weight-black   text-capitalize" outlined color="grey lighten-3">
            From: 13. Aug 2020</v-btn>
        <v-btn class="mx-1 my-2 px-2 font-weight-black   text-capitalize" outlined color="grey lighten-3">
            To: 28. Aug 2020</v-btn>
        <p class="ma-0   text-capitalize d-block d-md-flex grey--text text--lighten-2">Item Count: 2</p>
    </div>
    <div class="nav__right_side d-flex align-center ml-md-auto flex-wrap justify-center">
        <v-btn class="mx-1 my-2 px-2 font-weight-black   text-capitalize" outlined color="grey lighten-3">
            <v-icon class="mr-1">
                mail_outline
            </v-icon>
            Send via email
        </v-btn>
        <v-btn class="mx-1 my-2 px-2 font-weight-black   text-capitalize" outlined color="grey lighten-3">
            <v-icon class="mr-1">
                print
            </v-icon>
            Print
        </v-btn>
        <v-btn class="mx-1 my-2 px-2 font-weight-black   text-capitalize" outlined color="grey lighten-3">
            <v-icon class="mr-1">
                picture_as_pdf
            </v-icon>
            PDF
        </v-btn>
        <v-btn class="mx-1 my-2 px-2 font-weight-black   text-capitalize" outlined color="grey lighten-3">
            <v-icon class="mr-1">
                picture_as_pdf
            </v-icon>
            CSV
        </v-btn>
    </div>
    <transition name="slide">
        <div class="filter__dropdown" v-if="filter">
            <div class="d-flex filter__sub">
                <div class="left__side">
                    <ul class="tag_list">
                        <li class="is-active">Time Intervals</li>
                        <li>External</li>
                        <li>Internal</li>
                        <li>Status</li>
                        <li>Reporter</li>
                        <li>Description</li>
                        <li>id</li>
                    </ul>
                </div>
                <div class="right__side">
                    <ul class="tag_list">
                        <li>Time Intervals</li>
                        <li>External</li>
                        <li>Internal</li>
                        <li>Status</li>
                        <li>Reporter</li>
                        <li>Description</li>
                        <li>id</li>
                        <li>Time Intervals</li>
                        <li>External</li>
                        <li class="is-active"> Internal</li>
                        <li>Status</li>
                        <li>Reporter</li>
                        <li>Description</li>
                        <li>id</li>
                        <li>Time Intervals</li>
                        <li>External</li>
                        <li>Internal</li>
                        <li>Status</li>
                        <li>Reporter</li>
                        <li>Description</li>
                        <li>id</li>
                    </ul>

                    <div class="input__group_main">
                        <input type="text" class="input__filter" placeholder="Reporter name">
                        <input type="text" class="input__filter" placeholder="Description">
                        <input type="text" class="input__filter" placeholder="Report ID">
                    </div>
                </div>

            </div>
            <div class="filter__footer d-flex justify-center py-1" @click="filterShow">
                <v-icon>
                    keyboard_arrow_up
                </v-icon> Save Filter
            </div>
        </div>
    </transition>

</div>
</template>

<script>
export default {
    data() {
        return {
            filter: false
        }
    },
    methods: {
        filterShow() {
            this.filter = !this.filter
        }
    }
}
</script>

<style lang="scss">
.second__nav {
    background: #2392db;
    position: relative;
}

.filter__sub {
    padding: 10px;
}

.filter__dropdown {
    position: absolute;
    top: 52px;
    width: 100%;
    background: #eee;
    z-index: 99;

}

.left__side {
    padding-right: 20px;
    border-right: 1px solid #ddd;

    .tag_list {
        list-style: none;
        display: flex;
        flex-direction: column;
        align-items: flex-end;

        li {
            padding: 4px 9px;
            background: #d8d8d8;
            border-radius: 10px;
            margin: 3px;
            cursor: pointer;
            font-size: 14px;

            &:hover {
                background: #aaaaaa;
                color: white;
            }
        }
    }
}

.right__side {
    width: 700px;

    .tag_list {
        list-style: none;
        display: flex;
        flex-wrap: wrap;

        li {
            padding: 4px 9px;
            background: #d8d8d8;
            border-radius: 10px;
            margin: 3px;
            cursor: pointer;
            font-size: 14px;

            &:hover {
                background: #aaaaaa;
                color: white;
            }
        }
    }
}

.tag_list li.is-active {
    background-color: #2392db !important;
    color: white;
}

.filter__footer {
    background: #c0c0c0 !important;
    cursor: pointer;

    .v-icon {
        font-weight: bold;
    }
}

.input__group_main {
    display: flex;
    flex-direction: column;
    margin-left: 20px;
    margin-top: 15px;

    .input__filter {
        outline: 0;
        border: 1px solid #ccc;
        margin: 2px 5px;
        padding: 5px 10px;
        border-radius: 10px;
        width: 200px;
        background: #fff;
        height: 30px;
        color: #bababa;
    }
}

::placeholder {
    /* Chrome, Firefox, Opera, Safari 10.1+ */
    color: #bababa;
    opacity: 1;
    /* Firefox */
}

:-ms-input-placeholder {
    /* Internet Explorer 10-11 */
    color: #bababa;
}

::-ms-input-placeholder {
    /* Microsoft Edge */
    color: #bababa;
}
</style>

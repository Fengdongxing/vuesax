<template>
    <div class="center">
        <vs-button
             icon
            :active="active == 0"
            @click="active = 0"
        >
            <i class="bx bx-home-alt"></i>
        </vs-button>
        <vs-button
            icon
            color="success"
            flat
            :active="active == 1"
            @click="active = 1"
        >
            <i class="bx bxs-phone-call"></i>
        </vs-button>
        <vs-button
                icon
                color="danger"
                border
                :active="active == 2"
                @click="active = 2"
        >
            <i class="bx bxs-heart"></i>
        </vs-button>
        <vs-button
                icon
                color="#7d33ff"
                relief
                :active="active == 3"
                @click="active = 3"
        >
            <i class="bx bxs-paper-plane"></i>
        </vs-button>
        <vs-button
                icon
                color="rgb(59,222,200)"
                gradient
                :active="active == 6"
                @click="active = 6"
        >
            <i class="bx bxs-purchase-tag"></i>
        </vs-button>
    </div>
</template>

<script>

    export default {
        data() {
            return {
                active: 0,
            }
        },
        methods:{

        }
    }
</script>

<style scoped>
.center {
    margin-top: 30px;
}
</style>

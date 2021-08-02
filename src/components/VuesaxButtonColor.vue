<template>
    <div class="center">
        <vs-button
            :active="active == 0"
            @click="active = 0"
        >Default</vs-button>
        <vs-button
            success
            flat
            :active="active == 1"
            @click="active = 1"
        >Default</vs-button>
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

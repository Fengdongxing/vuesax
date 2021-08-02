<template lang="html">
    <div class="center">
        <vs-button
            flat
            :active="active == 0"
            @click="active = 0"
        >Active</vs-button>
        <vs-button
            flat
            :active="active == 2"
            @click="active = 2"
        >Default</vs-button>
        <vs-button disabled>Disabled</vs-button>
    </div>
</template>

<script>

    export default {
        data:() => ({
            active: 0,
        }),
        methods:{

        }
    }
</script>

<style scoped>
.center {
    margin-top: 30px;
}
</style>

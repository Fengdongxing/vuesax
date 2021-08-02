<template>
    <div class="center">
        <vs-button
            :active="active == 0"
            @click="active = 0"
        >Active</vs-button>
        <vs-button
                :active="active == 2"
                @click="active = 2"
        >Default</vs-button>
        <vs-button disabled>Disabled</vs-button>
    </div>
</template>

<script>

    export default {
        data(){
            return {
                active: 0,
            }
        },
        methods:{

        }
    }
</script>

<style scoped>
.button-demo1 {
    margin-top: 30px;
}
</style>

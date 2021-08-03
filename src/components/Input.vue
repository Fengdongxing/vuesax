<template>
    <div class="input-parent">
        <div class="mt30 center">
            <vs-input v-model="value" placeholder="Name" />
        </div>
        <div class="mt30 center">
            <vs-input v-model="value" placeholder="Evan You" label="Name" />
        </div>
        <div class="mt30 center">
            <vs-input v-model="value3" label-placeholder="Country" />
        </div>
        <div class="mt30 center content-inputs">
            <vs-input
                    primary
                    v-model="value10"
                    placeholder="Primary" />

            <vs-input
                    success
                    v-model="value2"
                    placeholder="Success" />

            <vs-input
                    danger
                    v-model="value3"
                    placeholder="Danger" />

            <vs-input
                    warn
                    v-model="value4"
                    placeholder="Warn" />

            <vs-input
                    dark
                    v-model="value5"
                    placeholder="Dark" />

            <vs-input
                    color="#7d33ff"
                    v-model="value6"
                    placeholder="HEX" />

            <vs-input
                    color="rgb(59,222,200)"
                    v-model="value7"
                    placeholder="HEX" />
        </div>
    </div>
</template>

<script>

    export default {
        data(){
            return {
                value3: '',
                value2: '',
                value4: '',
                value5: '',
                value6: '',
                value7: '',
                value8: '',
                value9: '',
                value10: '',
            }
        },
        methods:{

        }
    }
</script>
<style lang="scss">
    .content-inputs {
        .vs-input-content {
            margin: 10px;
        }
    }
</style>
<style lang="scss" scoped>
.input-parent {
    width: 960px;
    margin: 0 auto;
}
    /*.content-inputs {*/
    /*    /deep/ .vs-input-content {*/
    /*        margin: 10px;*/
    /*    }*/
    /*}*/

</style>

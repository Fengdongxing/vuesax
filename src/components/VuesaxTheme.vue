<template>
    <div class="center">
        <vs-button color="primary">Alert Primary</vs-button>
        <vs-button color="success">Alert Success</vs-button>
        <vs-button color="danger">Alert Danger</vs-button>
        <vs-button color="warning">Alert Warning</vs-button>
        <vs-button color="dark">Alert Dark</vs-button>
        <vs-button color="primary">Alert Color RGB | HEX</vs-button>
        <vs-button
                @click="editThemeHandle"
                color="primary"
        >function修改主题颜色</vs-button>
    </div>
</template>

<script>
    // 修改主题可以有几种方式，一是在main 的Vue.use(Vuesax,{ colors: { primary:'#5b3cc4',
    // success:'rgb(23, 201, 100)',
    //     danger:'rgb(242, 19, 93)',
    //     warning:'rgb(255, 130, 0)',
    //     dark:'rgb(36, 33, 69)'  } })
    // 2是: css， :root{
    //  --vs-primary: 91, 60, 196
    // --vs-success: 23, 201, 100
    // --vs-danger: 242, 19, 93
    // --vs-warn: 254, 130, 0
    // --vs-dark: 36, 33, 69
    //
    //
    // }
    export default {
        data() {
            return {

            }
        },
        methods:{
            editThemeHandle(){
                // 是不是只是修改颜色,而不是修改主题?
                this.$vs.setColor('primary', '#000')
            }
        }
    }
</script>

<style scoped>

</style>

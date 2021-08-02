<template>
    <div class="center grid">
        <vs-row>
            <vs-col vs-type="flex" vs-justify="center" vs-align="center" w="12">
                100%
            </vs-col>
        </vs-row>

        <vs-row>
            <vs-col :key="index" v-for="col,index in 2" vs-type="flex" vs-justify="center" vs-align="center" w="6">
                50%
            </vs-col>
        </vs-row>

        <vs-row>
            <vs-col :key="index" v-for="col,index in 3" vs-type="flex" vs-justify="center" vs-align="center" w="2">
                33.3%
            </vs-col>
        </vs-row>

<!--        <vs-row justify="flex-end" align="center">-->
        <vs-row justify="flex-end" align="center">
            <vs-col class="col-box" :key="index" v-for="col,index in 3" vs-type="flex" vs-justify="center" vs-align="center" w="3">
                <div class="self-debug">25%</div>
            </vs-col>
        </vs-row>

        <vs-row>
            <vs-col :key="index" v-for="col,index in 6" vs-type="flex" vs-justify="center" vs-align="center" w="2">
                16.6%
            </vs-col>
        </vs-row>

        <vs-row>
            <vs-col :key="index" v-for="col,index in 12" vs-type="flex" vs-justify="center" vs-align="center" w="1">
                8.3%
            </vs-col>
        </vs-row>
        <vs-row>
            <vs-col w="2">
                <div class="bg1">
                    2份有背景色
                </div>
            </vs-col>
            <vs-col w="3">
                <div class="bg2">
                    3份有背景色
                </div>
            </vs-col>
            <vs-col w="5">
                <div class="bg3">
                    8份有背景色
                </div>
            </vs-col>
<!--            <vs-col w="2">-->
<!--                <div class="bg4">-->
<!--                    2份有背景色-->
<!--                </div>-->
<!--            </vs-col>-->
        </vs-row>
    </div>
</template>

<script>
    export default {
        name: "Grid"
    }
</script>

<style scoped>
.bg1 {
    background-color: skyblue;
    /*background-color: #000000;*/
    /*background-color: yellow;*/
}
    .bg2 {
        background-color: purple;
    }
    .bg3 {
        background-color: yellow;
    }
    .bg4 {
        background-color: hotpink;
    }
    .self-debug {
        /*background: #000;*/
        /*height: 100px;*/
    }
    .col-box {
        background: deepskyblue;
        height: 100px;
    }
</style>

<template>
    <div id="app">
        <div class="container">
            {{ testData }}
        </div>
    </div>
</template>

<script>
export default {
    name: 'home',
    components: {
    },
    data() {
        return {
            testData: null
        }
    },
    props: {
        data: {}
    },
    updated(){
    },
    mounted() {
        this.testData = '测试数据测试数据测试数据测试数据测试数据测试数据测试数据测试数据测试数据测试数据测试数据测试数据测试数据测试数据';
        
    },
    methods: {
    },
    computed: {

    }
}
</script>

<style lang="less" rel="stylesheet/less">
</style>

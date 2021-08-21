<template>
    <div>
<!--        header-->
        <div class="header">
            <input type="text" class="search" placeholder="请输入商家或商品名称">
        </div>
    </div>
</template>

<script>
    export default {
        name: "index",
        props: {},
        components: {},
        mounted: {},
        data() {
            return {}
        },
        methods: {},
    }
</script>

<style lang="scss" scoped>
    .header{
        background: #1c1b20;
        padding: 0.2rem;
        .search{
            width: 100%;
            border: none;
            height: 0.6rem;
            line-clamp: 0.6rem;
            border-radius: 0.3rem;
            padding: 0 0.2rem;
            box-sizing: border-box;
        }
    }
</style>
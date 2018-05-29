<template>
    <div class="container">
        <headerCon v-bind:headerCon="headerTit"></headerCon>
        <div class="content">
            <h3>欢迎来到我的个人中心</h3>
            <city></city>
        </div>
    </div>
</template>

<script>
    import Header from "@/common/components/Header";
    import City from "@/demo/City";
    import "@/common/style/common.css";

    export default {
        name: "My",
        data(){
            return{
                headerTit:"个人中心",
            }
        },
        components: {
            'headerCon': Header,
            'city':City,
        }
    }
</script>

<style scoped>

</style>
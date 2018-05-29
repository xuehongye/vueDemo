<template>
    <div class="container">
        <headerCon v-bind:headerCon="headerTit"></headerCon>
        <div class="content">
            <h3>欢迎来到商城</h3>
        </div>
    </div>
</template>
<script>
    import Header from "@/common/components/Header";
    import "@/common/style/common.css"
    export default {
        name: 'Shop',
        data(){
            return{
                headerTit:"商城",
            }
        },
        components: {
            'headerCon': Header,
        }
    }
</script>
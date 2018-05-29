<template>
    <div id="app">
        <div class="content">
            <router-view></router-view>
        </div>
        <tab></tab>
    </div>
</template>


<script>
    import Tab from "@/common/components/Tab";
    import "@/common/style/common.css"
    export default {
        name: 'App',
        components: {
            'Tab': Tab,
        },
    }
</script>

<style>
    #app {
        width: 100%;
        height:100vh;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
</style>

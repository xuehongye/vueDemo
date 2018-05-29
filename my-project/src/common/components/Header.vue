<template>
    <div class="header">
        {{headerCon}}
    </div>
</template>

<script>
    export default {
        name: "Header",
        props: ['headerCon']
    }
</script>

<style scoped>
.header{
    width: 100%;
    height: 50px;
    font-size: 22px;
    color:#000;
    background: #fff;
    text-align: center;
    line-height: 50px;
}
</style>
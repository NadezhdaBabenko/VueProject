<template>
    <button class="btn-main">
        find out more
    </button>
</template>

<style lang="scss">
    .btn-main {
        color: #fff;
        font-size: 13px;
        line-height: 21px;
        background-color: #e84545;
        padding: 12px 60px;
        border-radius: 2px;
        border: 1px solid transparent;
        text-align: center;
        text-transform: uppercase;
        font-weight: 600;
        &:hover {
            background-color: darken(#e84545, 5%);
        }
    }
</style>

<script>

    export default {
        name: 'App',

        data: () => ({
            //
        }),
    };
</script>

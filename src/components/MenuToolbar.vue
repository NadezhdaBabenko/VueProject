<template>
    <div>
        <MenuButton/>
        <MenuButton/>
        <MenuButton/>
        <MenuButton/>
        <MenuButton/>
    </div>
</template>

<script>
    import MenuButton from './MenuButton';

    export default {
        name: 'App',

        components: {
            MenuButton,
        },

        data: () => ({
            //
        }),
    };
</script>
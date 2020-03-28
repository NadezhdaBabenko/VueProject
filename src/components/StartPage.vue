<template>
    <div class="startPage">
        <Header/>
        <StartInfo/>

    </div>
</template>

<script>
    import Header from './Header';
    import StartInfo from './StartInfo';


    export default {
        name: 'App',

        components: {
            Header,
            StartInfo
        },

        data: () => ({
            //
        }),
    };
</script>

<style lang="scss">
    .startPage {
        background-image: url('../assets/imgs/main/main1.png'); 
        // height: 100vh;
    }


</style>





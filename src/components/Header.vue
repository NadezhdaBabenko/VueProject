<template>
    <div class="header container-fluid">
        <div class=" header__container container">
            <div class="row">
                <div class="header__logo col-2">
                    <img class="header__logo-img" src="../assets/imgs/main/active-box.png" alt="logo">
                </div>

                <Menu/>
            </div>

        </div>

    </div>
</template>

<style lang="scss">
    .header {
        &__logo {
            padding: .5rem 1rem;
            display: flex;
            align-items: center;
        }
        &__logo-img {
            width: 185px;
             height: 20px;
         }
    }
</style>

<script>
    import Menu from './Menu';

    export default {
        name: 'App',

        components: {
            Menu,
        },

        data: () => ({
            //
        }),
    };
</script>

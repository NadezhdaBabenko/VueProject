<template>
    <div class="startInfo">
        <div class="startInfo__title">
            Your Favorite One Page Multi Purpose Template
        </div>
        <div class="startInfo__text">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sit, porro est voluptate laboriosam et.
        </div>
        <div class="startInfo__btn-block">
            <BtnMain class="startInfo__btn" title="find out more"/>
        </div>
        
    </div>

</template>

<style lang="scss">
    .startInfo {
        padding-top: 150px;
        padding-bottom: 150px;
        &__title {
            font-size: 65px;
            line-height: 71px;
            color: #fff;
            font-weight: bold;
            text-align: center;
            width: 80%;
            margin: 0 auto;
        }
        &__text {
            font-size: 22px;
            line-height: 33px;
            color: #fff;
            text-align: center;
            width: 80%;
            margin: 0 auto;
            padding-top: 45px;
        }
        &__btn-block {
            margin-top: 80px;
            display: flex;
            justify-content: center;
        }
    }
    @media (max-width: 600px) {
        .startInfo {
            padding-top: 100px;
            padding-bottom: 100px;
            &__title {
                font-size: 40px;
                line-height: 60px;
            }
        }
    }

</style>

<script>
    import BtnMain from './BtnMain';

    export default {
        name: 'App',

        components: {
            BtnMain,
        },

        data: () => ({
            //
        }),
    };
</script>

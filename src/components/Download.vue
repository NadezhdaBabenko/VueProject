<template>
    <div class="download">
        <div class="download__title">
            Are You Ready to Start? Download Now For Free!
        </div>
        <div class="download__text">
            Fusce dapibus, tellus ac cursus commodo
        </div>
        <div class="download__btn-block">
            <BtnMain class="download__btn"/>
        </div>
    </div>
    
</template>

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

<style lang="scss">
    .download {
        text-align: center;
        &__title {
            font-size: 28px;
            line-height: 25px;
            padding-top: 100px;
        }
        &__text {
            color: #2d3033;
            padding: 25px 0 40px 0;
        }
        &__btn-block {
            margin-bottom: 100px;
        }
    }
</style>





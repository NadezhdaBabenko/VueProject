<template>
    <div class="feature">
            <img class="feature__icon" :src="require(`../assets/imgs/features/${src}`)" :alt="alt">
        <div class="feature__title">
            {{ title }}
        </div>
        <div class="feature__text">
            {{ text }}
        </div>
    </div>
</template>

<script>
export default {
    props: {
        src: String,
        title: String,
        text: String,
        alt: String
    }
}
</script>

<style lang="scss">
    .feature {
        &__icon {
        margin: 0 auto;
        display: block;
        }
        &__title {
            padding: 35px 0 30px 0;
            color: #2d3033;
            font-weight: bold;
            font-size: 14px;
            text-transform: uppercase;
            text-align: center;
        }
        &__text {
            color: #c4c7c9;
            font-size: 14px;
            text-align: center;
        }
    }
</style>



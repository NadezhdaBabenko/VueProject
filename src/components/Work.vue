<template>
    <div class="work">
        <div class="work__block">
            <img class="work__img" :src="require(`../assets/imgs/work/${src}`)" :alt="alt">
            <div class="work__info">
                <div class="work__title">
                    {{ title }}
                </div>
                <div class="work__text">
                    {{ text }}
                </div>
            </div>   
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
    .work {
        &__block {
            position: relative;
        }
        &__info {
            position: absolute;
            left: 50%;
            top: 50%;
        }
    }
</style>



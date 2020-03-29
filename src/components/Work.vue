<template>
    <div class="work">
        <div class="work__block">
            <img class="work__img" :src="require(`../assets/imgs/work/${src}`)" :alt="alt">
            <div class="work__info-block">
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
        cursor: pointer;
        &:hover {
            .work__info-block {
            display: flex;
            align-items: center;
            justify-content: center;
            }
        }
        &__block {
            position: relative;
        }
        &__img {
            width: 100%;
        }
        &__info-block {
            position: absolute;
            top: 0;
            left: 0;
            bottom: 0;
            right: 0;
            background-color: #e84545eb;
            display: none;
        }
        &__info {
            text-align: center;

        }
        &__title {
            font-size: 14px;
            color: #fff;
            font-weight: bold;
            text-transform: uppercase;
        }
        &__text {
            font-size: 14px;
            color: #fff;
        }
    }
</style>



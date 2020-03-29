<template>
    <div class="member">
        <img class="member__img" :src="require(`../assets/imgs/team/${src}`)" :alt="alt">
        <div class="member__info">
            <div class="member__name">
                {{ name }}
            </div>
            <div class="member__position">
                {{ position }}
            </div>
            <div class="member__description">
                {{ description }}
            </div>
            <div class="member__social">
                <a class="member__social-link" href="#">
                    <img src="../assets/imgs/social/social1.png">
                </a>
                <a class="member__social-link" href="#">
                    <img src="../assets/imgs/social/social2.png">
                </a>
                <a class="member__social-link" href="#">
                    <img src="../assets/imgs/social/social3.png">
                </a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        src: String,
        name: String,
        position: String,
        description: String,
        alt: String
    }
}
</script>

<style lang="scss">
    .member {
        &__name {
            font-size: 22px;
            color: #2d3033;
            padding: 25px 0 10px;

        }
        &__position {
            font-size: 13px;
            color: #ea5151;
            text-transform: uppercase;
            padding-bottom: 25px;
        }
        &__description {
            padding-bottom: 25px;
            font-size: 13px;
            color: #6c7279;
        }
        &__social-link {
            margin-right: 5px;
        }
    }
</style>



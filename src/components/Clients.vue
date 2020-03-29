<template>
    <div class="client">
        <agile :initial-slide="0">
            <div class="client__slide slide">
                <img class="client__img" src="../assets/imgs/main/client1.png"/>
                <div class="client__text-block">
                    <div class="client__title">
                        “Integer posuere erat a ante venenatis dapibus posuere velit al. ante venenatis dapibus posuere velit al"
                    </div>
                    <div class="client__text">
                        Susan Sims, Interaction Designer at XYZ
                    </div>
                </div>
            </div>
            <div class="client__slide slide">
                <img class="client__img" src="https://images.unsplash.com/photo-1529815481058-55e5b656f6d6?ixlib=rb-1.2.1&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb&amp;w=1600&amp;fit=max&amp;ixid=eyJhcHBfaWQiOjE0NTg5fQ"/>
                <div class="client__text-block">
                    <div class="client__title">
                        "Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fugiat corporis dolore ut, perferendis labore esse accusantium dolor."
                    </div>
                    <div class="client__text">
                        Susan Sims, Interaction Designer at XYZ
                    </div>
                </div>
            </div>
            <div class="client__slide slide">
                <img class="client__img" src="https://images.unsplash.com/photo-1523712999610-f77fbcfc3843?ixlib=rb-1.2.1&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb&amp;w=1600&amp;fit=max&amp;ixid=eyJhcHBfaWQiOjE0NTg5fQ"/>
                <div class="client__text-block">
                    <div class="client__title">
                        "Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit magnam harum id officiis!"
                    </div>
                    <div class="client__text">
                        Susan Sims, Interaction Designer at XYZ
                    </div>
                </div>
            </div>
            <div class="client__slide slide">
                <img class="client__img" src="https://images.unsplash.com/photo-1524260855046-f743b3cdad07?ixlib=rb-1.2.1&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb&amp;w=1600&amp;fit=max&amp;ixid=eyJhcHBfaWQiOjE0NTg5fQ"/>
                <div class="client__text-block">
                    <div class="client__title">
                        “Integer posuere erat a ante venenatis dapibus posuere velit al. ante venenatis dapibus posuere velit al"
                    </div>
                    <div class="client__text">
                        Susan Sims, Interaction Designer at XYZ
                    </div>
                </div>
            </div>
            <div class="client__slide slide">
                <img class="client__img" src="https://images.unsplash.com/photo-1519681393784-d120267933ba?ixlib=rb-1.2.1&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb&amp;w=1600&amp;fit=max&amp;ixid=eyJhcHBfaWQiOjE0NTg5fQ"/>
                <div class="client__text-block">
                    <div class="client__title">
                        "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia magni id odio fugit aliquam aliquid repellendus dolore alias provident expedita."
                    </div>
                    <div class="client__text">
                        Susan Sims, Interaction Designer at XYZ
                    </div>
                </div>
            </div>
            <img class="slide" src="https://images.unsplash.com/photo-1526080676457-4544bf0ebba9?ixlib=rb-1.2.1&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb&amp;w=1600&amp;fit=max&amp;ixid=eyJhcHBfaWQiOjE0NTg5fQ"/>
            <img class="slide" src="https://images.unsplash.com/photo-1519681393784-d120267933ba?ixlib=rb-1.2.1&amp;q=85&amp;fm=jpg&amp;crop=entropy&amp;cs=srgb&amp;w=1600&amp;fit=max&amp;ixid=eyJhcHBfaWQiOjE0NTg5fQ"/>
            <template slot="prevButton"><i class="fas fa-chevron-left"></i></template>
            <template slot="nextButton"><i class="fas fa-chevron-right"></i></template>
        </agile>
    </div>
</template>

<script>

</script>

<style lang="scss">
    .agile__nav-button {
    background: transparent;
    border: none;
    color: #fff;
    cursor: pointer;
    font-size: 24px;
    height: 100%;
    position: absolute;
    top: 0;
    -webkit-transition-duration: 0.3s;
            transition-duration: 0.3s;
    width: 80px;
    }
    .agile__nav-button:hover {
    background-color: rgba(0, 0, 0, 0.5);
    opacity: 1;
    }
    .agile__nav-button--prev {
    left: 0;
    }
    .agile__nav-button--next {
    right: 0;
    }
    .agile__dots {
    bottom: 10px;
    left: 50%;
    position: absolute;
    -webkit-transform: translateX(-50%);
            transform: translateX(-50%);
    }
    .agile__dot {
    margin: 0 10px;
    }
    .agile__dot button {
    background-color: #ffffff8f;
    border: 1px solid transparent;
    border-radius: 50%;
    cursor: pointer;
    display: block;
    height: 10px;
    font-size: 0;
    line-height: 0;
    margin: 0;
    padding: 0;
    -webkit-transition-duration: 0.3s;
            transition-duration: 0.3s;
    width: 10px;
    }
    .agile__dot--current button, .agile__dot:hover button {
    background-color: #fff;
    }

    .slide {
    display: block;
    height: 500px;
    -o-object-fit: cover;
        object-fit: cover;
    width: 100%;
    }

    .client {
        &__slide {
            display: flex!important;
            width: 100%;
        }
        &__img {
            width: 50%;
        }
        &__text-block {
            background-color: #53354a;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding-top: 10%;
        }
        &__title {
            font-size: 36px;
            line-height: 42px;
            color: #fff;
            font-family: Cardo;
            font-style: italic;
            width: 80%;
        }
        &__text {
            font-size: 13px;
            line-height: 21px;
            color: #fff;
            text-transform: uppercase;
            width: 80%;
        }
    }

    @media (max-width: 1000px) {
        .client {
            &__img {
                display: none;
            }
        }
    }
</style>





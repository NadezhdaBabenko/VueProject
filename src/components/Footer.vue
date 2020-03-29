<template>
    <div class="footer container-fluid">
        <div class="footer__container container">
            <div class="footer__row row">
                <div class="footer__block col-md-5">
                    <div class="footer__title">
                        Location
                    </div>
                    <div class="footer__text">
                        3481 Melrose Place Beverly Hills, CA 90210
                    </div>
                </div>
                <div class="footer__block col-md-2">
                    <div class="footer__title">
                        Share with love
                    </div>
                    <div class="footer__icons">
                        <a class="footer__icon-link" href="#">
                            <img class="footer__icon" src="../assets/imgs/socialFooter/social1.png">
                        </a>
                        <a class="footer__icon-link" href="#">
                            <img class="footer__icon" src="../assets/imgs/socialFooter/social2.png">
                        </a>
                        <a class="footer__icon-link" href="#">
                            <img class="footer__icon" src="../assets/imgs/socialFooter/social3.png">
                        </a>
                    </div>
                </div>
                <div class="footer__block col-md-5">
                    <div class="footer__title">
                        About Activebox
                    </div>
                    <div class="footer__text">
                        Cras justo odio, dapibus ac facilisis in, egestas eget quam. Dapibus ac facilisis in, egestas eget quam. 
                    </div>
                </div>
            </div>
        </div>
    </div>
    
</template>

<script>

</script>

<style lang="scss">
    .footer {
        background-color: #3a3e64;
        &__row {
            display: flex;
            justify-content: space-between;
            flex-direction: row;
            padding: 70px 0 90px;
        }
        &__block {
            text-align: center;
            min-width: 155px;
            // &:first-child {
            //     min-width: 270px;
            //     max-width: 300px;
            // }
            // &:last-child {
            //     min-width: 270px;
            //     max-width: 300px;
            // }
        }
        &__title {
            font-size: 14px;
            color: #d8d8e0;
            font-weight: bold;
            text-transform: uppercase;
            padding-bottom: 20px;
        }
        &__text {
            font-size: 14px;
            color: #757893;
        }
        &__icons {
            min-width: 135px;
        }
        &__icon {
            margin-right: 5px;
        }
    }

    @media (max-width: 991px) {
        .footer {
            &__row {
                justify-content: center;
                flex-direction: column;
            
            }
            &__block {
                margin: 0 auto;
                padding-bottom: 40px;
                &:last-child{
                    padding-bottom: 0;
                }
            }
            &__title {
                padding-bottom: 10px;
            }
        }
    }
</style>





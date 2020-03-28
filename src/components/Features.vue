<template>
    <div class="features container">
        <div class="features__row row">
            <Feature src="feature1.png"
            title="Easily Customised" 
            text="Cras justo odio, dapibus ac facilisis in, egestas eget quam. Nullam quis urna mollis omare vel eu leo. Donec ullamcorper nulla" 
            alt="feature"
            />

            <Feature src="feature2.png"
            title="Responsive REady" 
            text="Cras justo odio, dapibus ac facilisis in, egestas eget quam. Nullam quis urna mollis omare vel eu leo. Donec ullamcorper nulla" 
            alt="feature"
            />

            <Feature src="feature3.png"
            title="Modern Design" 
            text="Cras justo odio, dapibus ac facilisis in, egestas eget quam. Nullam quis urna mollis omare vel eu leo. Donec ullamcorper nulla" 
            alt="feature"
            />
        </div>

        <div class="features__row row">
            <Feature src="feature4.png"
            title="Clean Code" 
            text="Cras justo odio, dapibus ac facilisis in, egestas eget quam. Nullam quis urna mollis omare vel eu leo. Donec ullamcorper nulla" 
            alt="feature"
            />

            <Feature src="feature5.png"
            title="Ready to Ship" 
            text="Cras justo odio, dapibus ac facilisis in, egestas eget quam. Nullam quis urna mollis omare vel eu leo. Donec ullamcorper nulla" 
            alt="feature"
            />

            <Feature src="feature6.png"
            title="Download for Free" 
            text="Cras justo odio, dapibus ac facilisis in, egestas eget quam. Nullam quis urna mollis omare vel eu leo. Donec ullamcorper nulla" 
            alt="feature"
            />
        </div>

    </div>
    
</template>

<script>
    import Feature from './Feature';


    export default {
        name: 'App',

        components: {
            Feature,
        },

        data: () => ({
            //
        }),
    };
</script>

<style lang="scss">
    .features {
        &__row {
            display: flex;
            justify-content: space-between;
        }
        &__row:first-child > .feature {
            padding: 120px 0 35px;
        }
        &__row:last-child > .feature {
            padding: 35px 0 120px;
        }
        &__row > .feature {
            width: 30%;
        }
    }


    @media (max-width: 767px ) {
        .features {
            &__row:first-child > .feature {
                padding: 35px 0 35px;
            }
            &__row:last-child > .feature {
                padding: 35px 0 35px;
            }
            &__row {
                justify-content: center;
                    & > .feature {
                        width: 85%;
                    }
            }
        }
    }


</style>





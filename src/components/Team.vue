<template>
    <div class="team container">
        <div class="team__row row">
            <div class="team__member col-xl-3 col-lg-6 col-md-6">
                <Member src="team1.png"
                name="Ruth Woods" 
                position="Founder, CEO" 
                description="Fusce dapibus, tellus ac cursus commodo, tortor mauris condimen. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimen"
                alt="feature"
                />
            </div>
            <div class="team__member col-xl-3 col-lg-6 col-md-6">
                <Member src="team2.png"
                name="Timothy Reed" 
                position="Co-Founder, Developer" 
                description="Fusce dapibus, tellus ac cursus commodo, tortor mauris condimen. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimen"
                alt="feature"
                />
            </div>
            <div class="team__member col-xl-3 col-lg-6 col-md-6">
                <Member src="team3.png"
                name="Victoria Valdez" 
                position="UI Designer" 
                description="Fusce dapibus, tellus ac cursus commodo, tortor mauris condimen. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimen"
                alt="feature"
                />
            </div>
            <div class="team__member col-xl-3 col-lg-6 col-md-6">
                <Member src="team4.png"
                name="Beverly Little" 
                position="Data Scientist" 
                description="Fusce dapibus, tellus ac cursus commodo, tortor mauris condimen. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimen"
                alt="feature"
                />
            </div>
        </div>

       

    </div>
    
</template>

<script>
    import Member from './Member';


    export default {
        name: 'App',

        components: {
            Member,
        },

        data: () => ({
            //
        }),
    };
</script>

<style lang="scss">
    .team {
        &__row {
            display: flex;
            justify-content: space-between;
            
        }
        &__member {
            display: flex;
            justify-content: center;
            margin: 100px 0;
        }
        &__member > .member {
            width: 270px;
        }
    }

    @media (min-width: 777px) and (max-width: 1199px) {
        .team {
        &__member {
            margin: 50px 0;
        }
        }
    }

    @media (max-width: 776px) {
        .team {
        &__member {
            margin: 30px 0;
        }

        }
    }
</style>





<template>
   <div class="works container-fluid">
       <div class="works__row row">
            <Work class="works__item col-md-3 col-sm-6" src="work1.png"
            title="Project name" 
            text="User Interface Design" 
            alt="work1"
            />
            <Work class="works__item col-md-3 col-sm-6" src="work2.png"
            title="Project name" 
            text="User Interface Design" 
            alt="work1"
            />
            <Work class="works__item col-md-3 col-sm-6" src="work3.png"
            title="Project name" 
            text="User Interface Design" 
            alt="work1"
            />
            <Work class="works__item col-md-3 col-sm-6" src="work4.png"
            title="Project name" 
            text="User Interface Design" 
            alt="work1"
            />
       </div>

        <div class="works__row row">
            <Work class="works__item col-md-3 col-sm-6" src="work5.png"
            title="Project name" 
            text="User Interface Design" 
            alt="work1"
            />
            <Work class="works__item col-md-3 col-sm-6" src="work6.png"
            title="Project name" 
            text="User Interface Design" 
            alt="work1"
            />
            <Work class="works__item col-md-3 col-sm-6" src="work7.png"
            title="Project name" 
            text="User Interface Design" 
            alt="work1"
            />
            <Work class="works__item col-md-3 col-sm-6" src="work8.png"
            title="Project name" 
            text="User Interface Design" 
            alt="work1"
            />
       </div>
   </div>
    
</template>

<script>
    import Work from './Work';


    export default {
        name: 'App',

        components: {
            Work,
        },

        data: () => ({
            //
        }),
    };
</script>

<style lang="scss">
    .works {
        &__item {
            padding: 0;
        }
    }




</style>





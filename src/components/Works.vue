<template>
   <div class="works container-fluid">
       <div class="works__row row">
            <Work src="work1.png"
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
    




</style>





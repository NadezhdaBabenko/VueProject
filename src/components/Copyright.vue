<template>
    <div class="copyright container-fluid">
        <div class="copyright__text">
            Copyright © 2015 ActiveBox. All Rights Reserved Made with Y by 
        </div>
        <div class="copyright__text">
            Made with <span class="copyright__heart">&#10084; </span> <span class="copyright__name">by Kamal Chaneman</span> 
        </div>
    </div>
    
</template>

<script>

</script>

<style lang="scss">
    .copyright {
        background-color: #313454;
        &__text {
            color: #515266;
            font-size: 14px;
            text-align: center;
            &:first-child {
                padding-top: 30px;
            }
            &:last-child {
                padding-bottom: 30px;
            }
        }
        &__name {
            color: #d6d6dd;
        }
        &__heart {
            color: #e84545;
        }
    }
</style>





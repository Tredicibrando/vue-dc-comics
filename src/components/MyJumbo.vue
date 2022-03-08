<template>
    <div class="jumbotron">
        <div class="container">
            <div class="content__wrapper"> <span>{{text}}</span> </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'MyJumbo',
        
        data(){
            return{
                text: '--> Content goes here <--',
            }
        }
    }
</script>

<style lang="scss" scoped>

    $black: #1C1C1C;

    .jumbotron{
        width: 100%;
        background-color: $black;

        .container{
        max-width: 1600px;
        margin: 0 auto;

            .content__wrapper{
                padding: 40px 0;

                span{
                    color: white;
                    font-size: 24px;
                    font-weight: 700;
                }
            }
        }
    }
</style>
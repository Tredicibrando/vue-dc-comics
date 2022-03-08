<template>
    <div class="cta">
        <div class="container">
            <div class="cta__wrapper">
                <ul class="cta__list">
                    <li class="cta__item">
                        <figure>
                            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                        </figure>
                        <h4 class="cta__text">Digital Comics</h4>
                    </li>

                    <li class="cta__item">
                        <figure>
                            <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        </figure>
                        <h4 class="cta__text">DC Merchandise</h4>
                    </li>

                    <li class="cta__item">
                        <figure>
                            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                        </figure>
                        <h4 class="cta__text">Subscription</h4>
                    </li>

                    <li class="cta__item">
                        <figure>
                            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                        </figure>
                        <h4 class="cta__text">Comic shop locator</h4>
                    </li>

                    <li class="cta__item">
                        <figure>
                            <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                        </figure>
                        <h4 class="cta__text">DC power visa</h4>
                    </li>
                    
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'MyCta',

        data(){
            return{

            }
        }
    }
</script>

<style lang="scss" scoped>

// variabili
$blue: #0282F9;

    .cta{
        width: 100%;
        background-color: $blue;

        .container{
            max-width: 1600px;
            margin: 0 auto;

            .cta__wrapper{
                padding: 40px 0;

                .cta__list{
                    list-style: none;
                    display: flex;
                    align-items: center;
                    justify-content: space-between;
                    gap: 10px;
                    padding: 0 30px;

                    .cta__item{
                        display: flex;
                        align-items: center;
                        gap: 20px;

                        figure{
                            width: max-content;

                            img{
                                width: 45px;
                            }
                        }

                        .cta__text{
                            color: white;
                            font-family: 'Open Sans', sans-serif;
                            text-transform: uppercase;
                            font-weight: 300;
                        }

                    }
                }
            }
        }
    }



</style>
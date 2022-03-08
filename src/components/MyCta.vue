<template>
    <div class="cta">
        <div class="container">
            <div class="cta__wrapper">
                <ul class="cta__list">
                    <li v-for="(item, i) in items" :key="i" class="cta__item">
                        <figure>
                            <img v-bind:src="item.image" alt="">
                        </figure>
                        <h4 class="cta__text">{{item.text}}</h4>
                    </li>

                    <!-- <li class="cta__item">
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
                    </li> -->
                    
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
                items:[
                    {
                        image: require('../assets/img/buy-comics-digital-comics.png'),
                        text: 'Digital Comics',
                    },
                    {
                        image: require('../assets/img/buy-comics-merchandise.png'),
                        text: 'DC Merchandise',
                    },
                    {
                        image: require('../assets/img/buy-comics-subscriptions.png'),
                        text: 'Subscription',
                    },
                    {
                        image: require('../assets/img/buy-comics-shop-locator.png'),
                        text: 'Comic shop locator',
                    },
                    {
                        image: require('../assets/img/buy-dc-power-visa.svg'),
                        text: 'DC power visa',
                    },
                ],
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
                                height: 45px;
                            }
                        }

                        .cta__text{
                            color: white;
                            font-family: 'Open Sans', sans-serif;
                            text-transform: uppercase;
                            font-weight: 300;
                            font-size: 14px;
                        }

                    }
                }
            }
        }
    }



</style>
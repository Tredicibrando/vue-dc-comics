<template>
    <div class="footer">
        <div class="container">
            <div class="footer__wrapper">
                <div class="footer__list">
                    <div class="list_wrapper">
                        <ul class="footer__list__wrapper">
                        <h4 class="footer__title">DC Comics</h4>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        </ul>

                        <ul class="footer__list__wrapper">
                        <h4 class="footer__title">Shop</h4>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        </ul>
                    </div>

                    <div class="list_wrapper">
                        <ul class="footer__list__wrapper">
                        <h4 class="footer__title">DC</h4>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        </ul>
                    </div>

                    <div class="list_wrapper">
                        <ul class="footer__list__wrapper">
                        <h4 class="footer__title">Sites</h4>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        <li class="footer__list__item"><a href="#">Footer Item</a></li>
                        </ul>
                    </div>
                </div>

                <div class="footer__bg__img"></div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'MyFooter'
    }
</script>

<style lang="scss" scoped>

    .footer{
        position: relative;
        background-image: url(../assets/img/footer-bg.jpg);
        background-size: 100%;
        background-repeat: no-repeat;
        background-position: center;
        

        .container{
            max-width: 1600px;
            margin: 0 auto;

            .footer__wrapper{
                display: flex;
                width: 100%;

                .footer__list{
                    padding: 40px 0;
                    flex-grow: 1;
                    display: flex;
                    gap: 30px;

                    .list_wrapper{
                        padding: 0 10px;


                        .footer__list__wrapper{
                        list-style: none;
                        color: white;
                        width: max-content;

                        .footer__title{
                            font-size: 18px;
                            font-weight: 700;
                            padding: 10px 0;
                            text-transform: uppercase;
                        }

                        .footer__list__item{
                            color: #959595;

                            a{
                                text-decoration: none;
                                color: currentColor;
                                font-size: 14px;
                            }
                        }
                    }
                    }

                    
                    
                }

                .footer__bg__img{
                    flex-grow: 1;
                    background-image: url(../assets/img/dc-logo-bg.png);
                    background-repeat: no-repeat;
                    background-size: 75%;
                    background-position: center right;
                }
            }
            
        }
    }



</style>
<template>
    <div class="social">
        <div class="container">
            <div class="social__wrapper">
                <div class="social__button">
                    <input class="signup__button" type="button" value="SIGN-UP NOW!">
                </div>
                <div class="social__cta">
                    <h4 class="social__text">Follow Us</h4>
                    <ul class="social__list">

                        <li class="social__list__item">
                            <img src="../assets/img/footer-facebook.png" alt="">
                        </li>

                        <li class="social__list__item">
                            <img src="../assets/img/footer-twitter.png" alt="">
                        </li>

                        <li class="social__list__item">
                            <img src="../assets/img/footer-youtube.png" alt="">
                        </li>

                        <li class="social__list__item">
                            <img src="../assets/img/footer-pinterest.png" alt="">
                        </li>

                        <li class="social__list__item">
                            <img src="../assets/img/footer-periscope.png" alt="">
                        </li>

                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'MySocial',
        data(){
            return{

            }
        }
    }

</script>

<style lang="scss" scoped>

$grey: #303030;
$blue: #0282F9;

.social{
    background-color: $grey;
    width: 100%;

    .container{
        max-width: 1600px;
        margin: 0 auto;

        .social__wrapper{
            display: flex;
            align-content: center;

            .social__button{
                flex-grow: 1;
                padding: 20px 0;

                .signup__button{
                    padding: 8px 15px;
                    background-color: transparent;
                    border: 2px solid $blue;
                    color: white;
                    line-height: 22px;
                }

            }

            .social__cta{
                flex-grow: 1;
                display: flex;
                justify-content: center;
                align-items: center;
                padding: 20px 0;

                .social__text{
                    color: $blue;
                    text-transform: uppercase;
                    font-size: 22px;
                    padding-right: 15px;
                }

                .social__list{
                    display: flex;
                    align-items: center;
                    list-style: none;
                    justify-content: space-between;
                    gap: 15px;

                    .social__list__item{
                        width: max-content;
                        img{
                            width: 30px;
                            display: block;
                        }
                    }
                }
            }

        }
    }

}

</style>
<template>
    <div class="container">
        <header class="main_header">
            <figure class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </figure>
            <div class="navbar">
                <ul class="navbar__list">
                    <li class="navbar__item">
                        <a href="#">Characters</a>
                    </li>
                    <li class="navbar__item">
                        <a href="#">Comics</a>
                    </li>
                    <li class="navbar__item">
                        <a href="#">Movies</a>
                    </li>
                    <li class="navbar__item">
                        <a href="#">TV</a>
                    </li>
                    <li class="navbar__item">
                        <a href="#">Games</a>
                    </li>
                    <li class="navbar__item">
                        <a href="#">Collectibles</a>
                    </li>
                    <li class="navbar__item">
                        <a href="#">Videos</a>
                    </li>
                    <li class="navbar__item">
                        <a href="#">Fans</a>
                    </li>
                    <li class="navbar__item">
                        <a href="#">News</a>
                    </li>
                    <li class="navbar__item">
                        <a href="#">Shop</a>
                    </li>
                </ul>
            </div>
        </header>
    </div>
</template>

<script>
    export default {
        name: 'MyHeader'
    }
</script>

<style lang="scss" scoped>

.container{
    width: 1420px;
    margin: 0 auto;

    .main_header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 10px;
        background-color: white;



        .logo{
        max-width: 100px;
    }

    .navbar{
        display: flex;
        align-items: center;
        padding: 10px 0;

        .navbar__list{
            display: contents;
            list-style: none;
        }

        .navbar__item{
            text-transform: uppercase;
            padding: 5px;

            a{
                color: currentColor;
                text-decoration: none;
            }
        }
    }
    }
    
    
}




</style>
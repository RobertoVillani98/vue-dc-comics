<template>
   
    <footer>
        <!-- footer top -->
        <div class="shop">
            <div class="container">
                
                <div class="box">
                    <a href="#">
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                        <span>digital comics</span>
                    </a>
                </div>

                <div class="box">
                    <a href="#">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        <span>dc merchandise</span>
                    </a>
                </div>

                <div class="box">
                    <a href="#">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                        <span>subscription</span>
                    </a>
                </div>

                <div class="box">
                    <a href="#">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                        <span>comic shop locator</span>
                    </a>
                </div>

                <div class="box">
                    <a href="#">
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                        <span>dc power visa</span>
                    </a>
                </div>
            </div>
        </div>

    </footer>

</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>
@import '../assets/style/partials/variables.scss';
.shop {
    background-color: $mainColor;
    padding: 50px 0;
    .container {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
    
        .box{
            min-width: 200px;
            a {
                margin: 20px 0;
                display: flex;
                align-items: center;
                img {
                    max-height: 50px;
                }
                span {
                    color: #fff;
                    text-transform: uppercase;
                    white-space: nowrap;
                    margin-left: 15px;
                }
            }
        }
    }
}
</style>
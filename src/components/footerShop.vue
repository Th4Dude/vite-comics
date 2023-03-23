<script>

export default {
    data() {
        return {
            name: 'footerShop'
        }
    }
}

</script>
<template>
    <div class="main_container">

        <div class="container_icons">
            <div class="flex">
                <img src="/buy-comics-digital-comics.png" alt="">
                <h3>Digital Comics</h3>
            </div>
            <div class="flex">
                <img src="/buy-comics-merchandise.png" alt="">
                <h3>DC Merchandise</h3>
            </div>
            <div class="flex">
                <img src="/buy-comics-subscriptions.png" alt="">
                <h3>Subscription</h3>
            </div>
            <div class="flex">
                <img src="/buy-comics-shop-locator.png" alt="">
                <h3>Comics Shop Locator</h3>
            </div>
            <div class="flex">
                <img src="/buy-dc-power-visa.svg" alt="">
                <h3>DC Power Visa</h3>
            </div>




        </div>


    </div>
</template>
<style lang="scss" scoped>
.main_container {

    background-color: #0282f9;
    width: 100%;
    height: 160px;
    display: flex;
    justify-content: center;
    align-items: center;

    .container_icons {
        max-width: 1200px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .flex {
        display: flex;
    }

    img {
        width: 40px;
        height: 50px;
    }

    h3 {
        color: white;
        padding: 0 25px;

    }
}
</style>
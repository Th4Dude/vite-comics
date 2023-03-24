<script>

export default {
    data() {
        return {
            name: 'footerShop',
            cards: [
                {
                    name: "DIGITAL COMICS",
                    image: "/buy-comics-digital-comics.png",
                },
                {
                    name: "DC MERCHANDISE",
                    image: "/buy-comics-merchandise.png",
                },
                {
                    name: "SUBSCRIPTION",
                    image: "/buy-comics-subscriptions.png",
                },
                {
                    name: "COMIC SHOP LOCATOR",
                    image: "/buy-comics-shop-locator.png",
                },
                {
                    name: "DC POWER VISA",
                    image: "/buy-dc-power-visa.svg",
                },
            ]
        }
    }
}
</script>

<template>
    <div class="main_container">
        <div class="container_icons">
            <div v-for="button in cards" class="flex">
                <div class="img flex"><img :src="button['image']" alt="">
                    <h3>{{ button.name }}</h3>
                </div>
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
        max-width: 1400px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .flex {
        display: flex;
        align-items: center;
    }

    img {
        width: 40px;
        height: 50px;
        cursor: pointer;
    }

    h3 {
        color: white;
        padding: 0 25px;
        cursor: pointer;

    }
}
</style>
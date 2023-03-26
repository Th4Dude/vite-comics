<script>

export default {
    data() {
        return {
            name: 'footerInfo',
            comics: [
                "Characters",
                "Comics",
                "Movies",
                "TV",
                "Games",
                "Videos",
                "News"
            ],
            shop: [
                "Shop DC",
                "Shop DC Collectibles"
            ],
            dc: [
                "Terms Of Use",
                "Privacy policy (New)",
                "Ad Choices",
                "Advertising",
                "Jobs",
                "Subscriptions",
                "Talent Workshops",
                "CPSC Certificates",
                "Ratings",
                "Shop Help",
                "Contact Us"
            ],
            sites: [
                "DC",
                "MAD Magazine",
                "DC Kids",
                "DC Universe",
                "DC Power Visa"
            ]
        }
    }
}

</script>
<template>

    <div class="container_info">
        <div class="container_list_info">
            <div class="padding-5">
                <!-- v-for-info -->
                <div>
                    <h3>DC COMICS</h3>
                    <li v-for="comic in comics"><a href="#">{{ comic }}</a></li>
                </div>
                <div>
                    <h3>SHOP</h3>
                    <li v-for="shop in shop"><a href="#">{{ shop }}</a></li>
                </div>
            </div>
            <div class="padding-5">
                <h3>DC</h3>
                <li v-for="dc in dc"><a href="#">{{ dc }}</a></li>
            </div>
            <div class="padding-5">
                <h3>SITE</h3>
                <li v-for="sites in sites"><a href="#">{{ sites }}</a></li>
            </div>
            <!-- v-for-info -->
        </div>
        <!-- img logo  -->
        <div>
            <img class="logo" src="/dc-logo-bg.png" alt="">
        </div>
        <!-- img logo  -->

    </div>

</template>

<style lang="scss" scoped>
.container_info {
    width: 100%;
    background-image: url(/footer-bg.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    justify-content: center;
    padding-top: 25px;
    position: relative;
    .padding-5 {
        padding: 20px 20px;
    }
}

.container_list_info {
    display: flex;
    width: 1200px;
}

div h3 {
    color: white;
    margin: 0;
    padding: 10px;
    cursor: pointer;
}

a {
    color: #959595;
    margin: 0;
    padding: 15px 10px;
    text-decoration: none;
}
a:hover {
        color: #0c7cec;
    }

li {
    list-style: none;
    padding-top: 5px;
}

.logo {
    position: absolute;
    width: 500px;
    height: 500px;
    top: -50px;
    right: 300px;
}
</style>
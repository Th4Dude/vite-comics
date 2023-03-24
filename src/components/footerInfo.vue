<script>

export default {
    data() {
        return {
            name: 'footerInfo'
        }
    }
}

</script>
<template>
    <div class="container_info">

        <div class="container_list_info">

            <div class="padding-5">
                <div>
                    <h3>DC COMICS</h3>
                    <h5>Comics</h5>
                    <h5>PG</h5>
                    <h5>Background</h5>
                    <h5>Whitelist</h5>
                    <h5>LetsgoToSee</h5>
                    <h5>Yeaa</h5>
                    <h5>Davaiii</h5>
                </div>
                <div>
                    <h3>SHOP</h3>
                    <h5>Comics</h5>
                    <h5>PG</h5>
                    <h5>Background</h5>
                </div>
            </div>
            <div class="padding-5">
                <h3>DC</h3>
                <h5>Comics</h5>
                <h5>PG</h5>
                <h5>Background</h5>
                <h5>Whitelist</h5>
                <h5>LetsgoToSee</h5>
                <h5>Yeaa</h5>
                <h5>Davaiii</h5>
            </div>
            <div class="padding-5">
                <h3>SITE</h3>
            <h5>Comics</h5>
            <h5>PG</h5>
                <h5>Background</h5>
                <h5>Whitelist</h5>
                <h5>LetsgoToSee</h5>
                <h5>Yeaa</h5>
                <h5>Davaiii</h5>
            </div>

        </div>
        <!-- <div >
                <img class="logo" src="/dc-logo-bg.png" alt="">
            </div> -->

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

    .padding-5 {
        padding-right: 20px;
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
}

div h5 {
    color: lightgrey;
    margin: 0;
    padding: 5px 10px;
}

.logo {
    width: 80%;
}
</style>
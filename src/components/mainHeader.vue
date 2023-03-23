
<script>
export default {
    data() {
        return {
            name: 'mainHeader'
        }
    }
}

</script>

<template>
    <section class="main_box">

        <div class="container_logo"><img src="/dc-logo.png" alt="logo"></div>

        <div class="container_list">

            <li><a href="">Character</a></li>
            <li><a href="">Comics</a></li>
            <li><a href="">Movies</a></li>
            <li><a href="">Tv</a></li>
            <li><a href="">Games</a></li>
            <li><a href="">Collectibles</a></li>
            <li><a href="">Videos</a></li>
            <li><a href="">Fans</a></li>
            <li><a href="">News</a></li>
            <li><a href="">Shop</a></li>

        </div>
    </section>
</template>

<style lang="scss" scoped>
.main_box {
    display: flex;
    width: 100%;
    justify-content: space-between;
    align-items: center;
    margin: 0 auto;

    .container_logo {
        width: 40%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .container_list {
        display: flex;
        justify-content: center;
        align-items: center;
        width: 60%;
    }
    .container_list li{
        list-style: none;
        padding:  0 20px;
    }
    a{
        text-decoration: none;
        color: #464646 ;
    }
    a:hover{
            color:blue;
        }
}

</style>

<script>

export default {
    data() {
        return {
            name: 'mainHeader',
            navbar: [
                'Characters',
                'Comics',
                'Movies',
                'TV',
                'Games',
                'Collectibles',
                'Videos',
                'Fans',
                'News',
                'Shop',
            ]
        }
    }
}

</script>

<template>
    <section class="main_box">
        <div class="container_logo_list">
            <!-- logo -->
            <div class="container_logo"><img src="/dc-logo.png" alt="logo"></div>
            <!-- logo -->
            <!-- navbar -->
            <div class="container_list">
                <li v-for="selector in navbar"><a href="#">{{ selector }}</a></li>
            </div>
            <!-- navbar -->
        </div>
    </section>
</template>

<style lang="scss" scoped>
.main_box {
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;

    .container_logo_list {
        display: flex;
        width: 1400px;
        justify-content: space-between;
        align-items: center;
        padding: 15px 0;
    }

    .container_list {
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .container_list li {
        list-style: none;
        padding: 0 10px;
        font-size: 18px;
    }

    a {
        text-decoration: none;
        color: #464646;
    }

    a:hover {
        color: #0c7cec;
        border-bottom: 3px solid #0c7cec;
    }
}
</style>
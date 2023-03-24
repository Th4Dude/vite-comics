<script>

export default {
    data() {
        return {
            name: 'footerSocial'
        }
    }
}

</script>
<template>
    <section class="main_container">
        <div class="container_btn_social">
            <div class="btn">
                <button>Sign-Up Now!</button>
            </div>
            <div class="social">
                <h4>FOLLOW US</h4>
                <ul>
                    <li><img src="/footer-facebook.png" alt=""></li>
                    <li><img src="/footer-periscope.png" alt=""></li>
                    <li><img src="/footer-pinterest.png" alt=""></li>
                    <li><img src="/footer-twitter.png" alt=""></li>
                    <li><img src="/footer-youtube.png" alt=""></li>
                </ul>
            </div>
        </div>

    </section>
</template>




<style lang="scss" scoped>
.main_container {
    position: absolute;
    z-index: 100;
    background-color: #303030;
    width: 100%;
    display: flex;
    justify-content: center;
}

.container_btn_social {
    width: 1400px;
    display: flex;
    justify-content: space-between;
    padding: 40px 0;
}

button {
    padding: 10px;
    border: 2px solid #0282f9;
    background-color: #303030;
    color: white;
    font-size: 20px;
    cursor: pointer;
}

.social {
    display: flex;
    justify-content: center;
    align-items: center;
}

.social h4 {
    color: #0282f9;
    font-size: 20px;
}

.social ul {
    display: flex;
    list-style: none;
    padding-left: 15px;
}

.social ul li {
    padding-right: 20px;
    color: grey;
}
</style>
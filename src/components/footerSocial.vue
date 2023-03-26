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
            <!-- btn -->
            <div>
                <button>Sign-Up Now!</button>
            </div>
            <!-- btn -->
            <div class="icons">
                <h4>FOLLOW US</h4>
                <!-- img-social -->
                <ul>
                    <button><img src="/footer-facebook.png" alt=""></button>
                    <button><img src="/footer-periscope.png" alt=""></button>
                    <button><img src="/footer-pinterest.png" alt=""></button>
                    <button><img src="/footer-twitter.png" alt=""></button>
                    <button><img src="/footer-youtube.png" alt=""></button>
                </ul>
                <!-- img-social -->
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
    align-items: center;
}

.container_btn_social {
    width: 1400px;
    display: flex;
    justify-content: space-between;
    align-items: center;
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

button:hover {
    transform: scale(1.1);
    transition: all 0.4s ease-out;
}

.icons {
    display: flex;
    justify-content: center;
    align-items: center;
}

.icons h4 {
    color: #0282f9;
    font-size: 20px;
}

.icons ul {
    display: flex;
    list-style: none;
    padding-left: 15px;
}

.icons ul button {
    padding-right: 20px;
    color: grey;
    border: none;
}

h4:hover {
    color: #0c7cec;
    border-bottom: 3px solid #0c7cec;
    cursor: pointer;
}
</style>
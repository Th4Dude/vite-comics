<script>
export default {
    data() {
        return {
            name: 'Main'
        }
    }
}

</script>
<template>
    <div class="main_container">
        <div class="background"></div>
        <div class="container_cards">
            <p>!</p>




        </div>






    </div>
</template>
<style lang="scss" scoped>
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}



.main_container {
    /* width: 100%;
        height: 200px;
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: #1c1c1c;
        color: white;
        margin-top: 10px; */

    .background {
        background-image: url(/jumbotron.jpg);
        background-size: cover;
        background-repeat: no-repeat;
        height: 400px;
        width: 100%;
    }

    .container_cards {
        height: 600px;
        width: 100%;
        background-color: #1c1c1c;
    }

}
</style>
<script>

export default {
    name: 'Card',
    props: {
        img: String,
        title: String
    }
}

</script>

<template>
    <div class="card">
        <div><img :src="img" alt=""></div>
        <h3>{{ title }}</h3>
    </div>
</template>

<style scoped>
.card {
    width: 200px;
}

img {
    width: 200px;
    height: 200px;
    transition: all 0.3s ease-out;
    cursor: pointer;
}

img:hover {
    transform: scale(1.1);
}

h3 {
    font-size: 12px;
    padding: 18px 0;
    color: white;

}
</style>
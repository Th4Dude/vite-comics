<script>

    import footerShop from './footerShop.vue';

    export default{
        data(){
            return {
            name : 'Footer'
            }
        },
        components :{
            footerShop,
        }

    }

</script>
<template>
    
    <footerShop></footerShop>

    <div class="container_info">
        <div>prima colonna</div>
        <div>seconda colonna</div>
        <div>terza colonna</div>
    </div>

</template>
<style scoped>




</style>
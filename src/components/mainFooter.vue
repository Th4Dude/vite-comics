<script>

    import footerShop from './footerShop.vue';
    import footerInfo from './footerInfo.vue';
    import footerSocial from './footerSocial.vue';

    export default{
        data(){
            return {
            name : 'Footer'
            }
        },
        components :{
            footerShop,
            footerInfo,
            footerSocial,
        }
    }

</script>
<template>
    
    <footerShop></footerShop>
    <footerInfo></footerInfo>
    <footerSocial></footerSocial>

</template>
<style scoped>




</style>
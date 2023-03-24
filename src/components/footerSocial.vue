<script>

    export default{
        data(){
            return {
            name : 'footerSocial'
            }
        }
    }

</script>
<template>

    <section>
        <div class="btn">
            <button>Sign-Up Now!</button>
        </div>
        <div class="social">
            <h4>FOLLOW US</h4>
            <ul>
                <li>Social</li>
                <li>Social</li>
                <li>Social</li>
                <li>Social</li>
                <li>Social</li>
            </ul>
        </div>
    </section>
    
    
</template>
<style lang="scss" scoped>

    section{
    background-color: #303030;
    display: flex;
    width: 100%;
    padding: 40px 0;
}
button{
    padding: 10px;
    border: 2px solid #0282f9;
    background-color: #303030;
    color: white;
    font-size: 20px;
}
.btn, .social{
    width: 50%;
    text-align: center;
}
.social{
    display: flex;
    justify-content: center;
    align-items: center;
}
.social h4 {
    color: #0282f9;
    font-size: 20px;
}
.social ul{
    display: flex;
    list-style: none;
    padding-left: 15px;
}
.social ul li{
    padding-right: 20px;
    color: grey;
}



</style>
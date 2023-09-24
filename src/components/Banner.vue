<template>
    <div id="main-banner">
        <h1 id="text-banner">Make Your Burguer</h1> 
        <div id="img-banner">
            <img src="/img/burguer.jpg" alt=""> 
        </div>
        
    </div>
</template>

<script>
export default {
    name: "Banner"
}
</script>

<style scoped>
    #main-banner {
       width: 100%;
       position: relative;
    }

    #text-banner {
        position: absolute;
        top: 270px;
        color: #FFF;
        left: 50px;
        font-size: 60px;
        background: #222;
        padding: 20px 40px;
    }

    #img-banner img {
        height: 630px;
        width: 100%;
        object-fit: cover;
    }
</style>
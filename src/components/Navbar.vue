<template>
    <nav id="nav">
        <router-link to="/">
            <img id="logo" :src="logo" :alt="alt">
        </router-link>
        <div>
            <router-link to="/">Início</router-link>
            <router-link to="/delivery">Pedidos</router-link>
        </div>
        
    </nav>
</template>

<script>
    export default {
        name: "Navbar",
        props: ["logo", "alt"]
    }
</script>

<style scoped>
    #nav {
        background: #222;
        border-bottom: 4px solid #111;
        padding: 15px 50px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    #logo {
        width: 45px;
        height: 45px;
    }

    #nav a {
        color: #FCBA03;
        text-decoration: none;
        margin: 12px;
        transition: color .2s;
    }

    #nav a:hover {
        color: #FFF;
    }
</style>
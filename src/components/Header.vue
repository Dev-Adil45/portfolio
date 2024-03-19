<template>
    <header>
        <img src="../../public/logo.png" alt="logo-Dev-Adil">
        <h1>Mon Portfolio</h1>
        <nav>
            <ul>
            <li><a href="">Acceuil</a></li>
            <li><a href="">Moi ?</a></li>
            <li><a href="">Contact</a></li>
            <li><a href="">Mes projets</a></li>
        </ul>
    </nav>
        
    </header>
</template>

<script setup>

</script>

<style scoped>


header {
        text-align: center;
        background-color: #FF3CAC;
        background-image: linear-gradient(225deg, #FF3CAC 0%, #784BA0 50%, #2B86C5 100%);
        padding: 50px 0px 5px 0px;
    }

img {
    text-align: center;
    max-width: 150px;
}
h1 {
    color: antiquewhite;
    font-size: 3rem;
    margin: 10px 0;
    padding: 20px;
}


nav {
    background-color: rgb(40, 38, 38);
    margin-top: 20px;
}
nav ul {
    display: flex;
    justify-content: space-evenly;
    list-style: none;
    padding: 0;
}
li {
    padding: 10px;
}
a {
    color: antiquewhite;
    text-decoration: none;
}

</style>
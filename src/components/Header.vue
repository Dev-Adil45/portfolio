<template>
    <header>
        <img src="../../public/logo.png" alt="logo-Dev-Adil">
        <h1>Mon Portfolio</h1>
        <nav id="navbar">
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
let lastScroll = 0;

window.addEventListener("scroll", () => {
  if (window.scrollY < lastScroll) {
    navbar.style.top = 0;
  } else {
    navbar.style.top = "-60px";
  }

  lastScroll = window.scrollY;
});
</script>

<style scoped>


header {
        text-align: center;
        background-color: #FF3CAC;
        background-image: linear-gradient(225deg, #FF3CAC 0%, #784BA0 50%, #2B86C5 100%);
        padding: 50px 0px 5px 0px;     
    }

img {
    max-width: 150px;
}
h1 {
    color: antiquewhite;
    font-size: 3rem;
    margin: 10px 0;
    padding: 20px;
}


nav {
    position: fixed;
    background-color: #FF3CAC;
    background-image: linear-gradient(225deg, #FF3CAC 0%, #784BA0 50%, #2B86C5 100%);
    height: 50px;
    min-width: 99%;
    top: 0;
    transition: 0.3s;
}
nav ul {
    display: flex;
    justify-content: space-evenly;
    list-style: none;
    padding: 0;
}

a {
    color: antiquewhite;
    text-decoration: none;
}

</style>
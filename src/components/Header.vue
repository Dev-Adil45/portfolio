<template>
    <header>
        <img src="../../public/logo.png" alt="logo-Dev-Adil">
        <h1>Mon Portfolio</h1>
        <nav id="navbar">
            <ul>
            <li><a href="">Acceuil</a></li>
            <li><a href="#AboutMe">Moi ?</a></li>
            <li><a href="#Competences">Compétences</a></li>
            <li><a href="">Contact</a></li>
            <li><a href="#Project">Mes projets</a></li>
        </ul>
    </nav>
        
    </header>
</template>

<style scoped>


header {
        width: 100vw;
        text-align: center;
        background-color: #FF3CAC;
        background-image: linear-gradient(225deg, #FF3CAC 0%, #784BA0 50%, #2B86C5 100%);
        padding: 50px 0px 0px 0px;     
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
    width: 100vw;
    top: 0;
    transition: 0.3s;
    z-index: 999;
}
nav ul {
    display: flex;
    justify-content: space-evenly;
    list-style: none;
    padding: 10px 0 0 0;
}

a {
    color: antiquewhite;
    text-decoration: none;
}


nav ul li {
    transition: 0.3s;
}
nav ul li:hover {
    font-size: 1.2rem;
    transition: 0.3s;
}

</style>
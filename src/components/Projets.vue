<template>
    <section>
    <div class="title-projet">
     <h2>Mes Projets</h2>
     <p>Hésitez pas a cliquer sur les liens en dessous des images pour plus de renseignements !</p>
    </div>
    <div class="container-projet">
     <div class="container">
        <h3>Mon CV</h3>
        <img src="../../public/Mon-CV.png" alt="Image de mon CV">
        <a href="">&#10145;Plus d'info&#11013;</a>
     </div>
     <div class="container">
        <h3>Espace commentaire dynamique</h3>
        <img src="../../public/Espace-commentaire.png" alt="Image site espace commentaire">
        <a href="">&#10145;Plus d'info&#11013;</a>
     </div>
     <div class="container">
        <h3>Mon Portfolio</h3>
        <img src="../../public/MonPortfolio.png" alt="Image site de mon portfolio">
        <a href="">&#10145;Plus d'info&#11013;</a>
     </div>
    </div>
    </section>

</template>


<style scoped>

section {
    background-color: #FF3CAC;
    background-image: linear-gradient(225deg, #FF3CAC 0%, #784BA0 50%, #2B86C5 100%);
    border-radius: 50px;
    display: flex;
    flex-direction: column;
    text-align: center;
    align-items: center;
    opacity: 0.6;
    transition: 0.3s;
}
section:hover {
    opacity: 1;
    background-color: #ff3caa60;
    background-image: linear-gradient(225deg, #ff3caa64 0%, #784ba069 50%, #2b85c56d 100%);
}

.container-projet {
    display: flex;
    justify-content: space-around;
}


.container {
    background-color: rgba(100, 224, 224, 0.638);
    border-radius: 50px;
    padding: 10px;
    margin: 10px;
    display: flex;
    justify-content: center;
    flex-direction: column;
    opacity: 0.7;
}
.container:hover {
    opacity: 1;
    transition: 0.3s;
    box-shadow: 5px 5px 20px 5px #000000; 
    box-shadow: 5px 5px 20px 5px #000000;
}
.title-projet {
    font-size: 1.5rem;
}
p {
    text-decoration: underline;
}

img {
    width: 350px;
    height: 350px;
    border-radius: 15px
}
a {
    font-size: 1.2rem;
}



</style>


<script setup>


</script>


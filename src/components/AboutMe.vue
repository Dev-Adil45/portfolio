<template>
    <div id="AboutMe">
    <h2>Qui suis-je ?</h2>
    <p>Je m'appelle Adil Bourkia, j'ai 25ans et je suis un passionné de technologies et de développement Web, toujours avide d'apprendre et de relever de nouveaux défis. Avec une solide base en HTML, CSS et JavaScript, je suis motivé pour mettre mes compétences au service de projets innovants et captivants. <br> Mon approche méthodique, ma capacité à résoudre des problèmes et ma volonté d'amélioration constante font de moi un développeur Web Junior déterminé à exceller dans ce domaine en pleine évolution !</p>
</div>

</template>

<script setup>

</script>

<style scoped>
#AboutMe {
    display: flex;
    flex-direction: column;
    width: 55%;
    margin: 0 auto;
    text-align: center;
    padding: 30px 20px;
    background-color: #FF3CAC;
    background-image: linear-gradient(225deg, #FF3CAC 0%, #784BA0 50%, #2B86C5 100%);
    border-radius: 50px;
    opacity: 0.7;
    transition: opacity 0.3s;
    transition: 0.2s;  
}

#AboutMe:hover {
    opacity: 1;
    transition: 0.2s;
    width: 56%;
    background-color: #ff3caa77;
        background-image: linear-gradient(225deg, #ff3caaa2 0%, #784ba09e 50%, #2b85c58c 100%);
}


</style>
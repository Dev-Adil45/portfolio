<template>
    <div id="PageErreur">
    <h1>Erreur 404</h1>
    <p>Cette page n'existe pas.</p><br>
    <p>Cliquez sur le bouton ci-dessous pour revenir sur la page d'acceuil.</p>

    <router-link :to="{name: 'home' }"><button id="btn-error">Retour</button></router-link></div>
</template>


<style scoped>
#PageErreur {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background-color: rgba(250, 235, 215, 0.937);
    border-radius: 30px;
    width: 40%;
    margin: 100px auto;
    padding: 20px;
}
#btn-error {
    margin-top: 20px;
    width: 150px;
    height: 50px;
    font-size: 1.3rem;
}
#btn-error:hover {
    background-color: blue;
    color: white;
    cursor: pointer;
}
h1 {
    color: red;
}


</style>
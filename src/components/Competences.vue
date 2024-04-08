<template>
  <section class="container-competences" id="Competences">
    <img src="../../public/ampoule.png" alt="icone-ampoule">
  <h2>Mes Compétences</h2>
  <article class="container">
        <h3 class="bubble">HTML5</h3>
        <div class="progress-bar">
            <div class="progress">90%</div>
        </div>
    </article>
    <article class="container">
        <h3 class="bubble">Blender</h3>
        <div class="progress-bar">
            <div class="progress1">50%</div>
        </div>
    </article>
    <article class="container">
        <h3 class="bubble">CSS</h3>
        <div class="progress-bar">
            <div class="progress2">75%</div>
        </div>
    </article>
    <article class="container">
        <h3 class="bubble">JavaScript</h3>
        <div class="progress-bar">
            <div class="progress1">50%</div>
        </div>
    </article>
    <article class="container">
        <h3 class="bubble">Vue.Js</h3>
        <div class="progress-bar">
            <div class="progress1">50%</div>
        </div>
    </article>
</section>
</template>

<script setup>


</script>

<style scoped>

img {
    display: block;
    margin: 0 auto; 
    width: 100px;
    height: 100px;
}



.container-competences {
    background-color: #ff3caa50;
    background-image: linear-gradient(225deg, #ff3caa71 0%rgba(120, 75, 1rgba(43, 133, 197, 0.334)79)A0 50%, #2B86C5 100%);
    padding: 15px;
    margin: 20px auto;
    display: flex;
    justify-content: space-around;
    flex-direction: column;
    text-align: center;
    border-radius: 50px;
    width: 65%;
    opacity: 0.7;
    transition: opacity 0.2s;
}
.container-competences:hover {
    opacity: 1;
    width: 66%;
    transition: 0.2s;
    background-color: #ff3caac1;
    background-image: linear-gradient(225deg, #ff3caab6 0%, #784ba0 50%rgba(43, 133, 197, 0.721)C5 100%);
}
 .container {
            display: flex;
            align-items: center;
            justify-content: space-between;
            width: 300px;
            margin: 20px auto;
        }

        .bubble {
            position: relative;
            background-color: #3498db;
            color: #fff;
            border-radius: 15px;
            padding: 10px 15px;
            font-family: Arial, sans-serif;
        }

        .progress-bar {
            flex: 1;
            height: 25px;
            background-color: #f1c40f;
            border-radius: 10px;
            margin-left: 10px;
            overflow: hidden;
            
        }

        .progress {
            width: 0%;
            height: 100%;
            background-color: #e67e22;
            text-align: center;
            transition: 1.5s;
        }

        .progress1 {
            width: 0%;
            height: 100%;
            background-color: #e67e22;
            text-align: center;
            transition: 1.5s;
        }

        .progress2 {
            width: 0%;
            height: 100%;
            background-color: #e67e22;
            text-align: center;
            transition: 1.5s;
        }

        #Competences:hover .progress {
            width: 90%;
            transition: 2s;
        }
        #Competences:hover .progress1 {
            width: 50%;
            transition: 2s;
        }
        #Competences:hover .progress2 {
            width: 75%;
            transition: 2s;
        }

</style>
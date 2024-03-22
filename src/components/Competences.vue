<template>
  <div class="container-competences" id="Competences">
    <img src="../../public/ampoule.png" alt="icone-ampoule">
  <h2>Mes Compétences</h2>
  <div class="container">
        <div class="bubble">HTML5</div>
        <div class="progress-bar">
            <div class="progress">90%</div>
        </div>
    </div>
    <div class="container">
        <div class="bubble">Blender</div>
        <div class="progress-bar">
            <div class="progress1">50%</div>
        </div>
    </div>
    <div class="container">
        <div class="bubble">CSS</div>
        <div class="progress-bar">
            <div class="progress2">75%</div>
        </div>
    </div>
    <div class="container">
        <div class="bubble">JavaScript</div>
        <div class="progress-bar">
            <div class="progress1">50%</div>
        </div>
    </div>
    <div class="container">
        <div class="bubble">Vue.Js</div>
        <div class="progress-bar">
            <div class="progress1">50%</div>
        </div>
    </div>
  </div>
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
    background-color: rgba(159, 184, 205, 0.745);
    padding: 15px;
    margin: 20px auto;
    display: flex;
    justify-content: space-around;
    flex-direction: column;
    text-align: center;
    border-radius: 50px;
    width: 65%;
    opacity: 0.8;
    transition: opacity 0.2s;
}
.container-competences:hover {
    opacity: 1;
    width: 68%;
    transition: 0.2s;
    background-color: rgba(159, 184, 205, 0.962);
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
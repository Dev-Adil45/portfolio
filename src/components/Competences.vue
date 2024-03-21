<template>
  <div class="container-competences" id="Competences">
  <h2>Mes Compétences</h2>
    <div class="container">
        <div class="bubble">HTML5</div>
        <div class="progress-bar">
            <div class="progress">90%</div>
        </div>
    </div>
    <div class="container1">
        <div class="bubble1">Blender</div>
        <div class="progress-bar1">
            <div class="progress1">50%</div>
        </div>
    </div>
    <div class="container2">
        <div class="bubble2">CSS</div>
        <div class="progress-bar2">
            <div class="progress2">75%</div>
        </div>
    </div>
    <div class="container3">
        <div class="bubble3">JavaScript</div>
        <div class="progress-bar3">
            <div class="progress3">50%</div>
        </div>
    </div>
  </div>
</template>

<script setup>


</script>

<style scoped>
.container-competences {
    background-color: rgba(159, 184, 205, 0.745);
    padding: 15px;
    margin: 20px auto;
    display: flex;
    justify-content: space-around;
    flex-direction: column;
    text-align: center;
    border-radius: 50px;
    width: 70%;
    opacity: 0.8;
    transition: opacity 0.3s;
    transition: 0.3s;
}
.container-competences:hover {
  opacity: 1;
  background-color: rgba(159, 184, 205, 0.962);
  width: 75%;
  transition: 0.3s;
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
            width: 90%;
            height: 100%;
            background-color: #e67e22;
            text-align: center;
        }

        .container1 {
            display: flex;
            align-items: center;
            justify-content: space-between;
            width: 300px;
            margin: 20px auto;
        }

        .bubble1 {
            position: relative;
            background-color: #3498db;
            color: #fff;
            border-radius: 15px;
            padding: 10px 15px;
            font-family: Arial, sans-serif;
        }

        .progress-bar1 {
            flex: 1;
            height: 25px;
            background-color: #f1c40f;
            border-radius: 10px;
            margin-left: 10px;
            overflow: hidden;
        }

        .progress1 {
            width: 50%;
            height: 100%;
            background-color: #e67e22;
            text-align: center;
        }

        .container2 {
            display: flex;
            align-items: center;
            justify-content: space-between;
            width: 300px;
            margin: 20px auto;
        }

        .bubble2 {
            position: relative;
            background-color: #3498db;
            color: #fff;
            border-radius: 15px;
            padding: 10px 15px;
            font-family: Arial, sans-serif;
        }

        .progress-bar2 {
            flex: 1;
            height: 25px;
            background-color: #f1c40f;
            border-radius: 10px;
            margin-left: 10px;
            overflow: hidden;
        }

        .progress2 {
            width: 75%;
            height: 100%;
            background-color: #e67e22;
            text-align: center;
        }

        .container3 {
            display: flex;
            align-items: center;
            justify-content: space-between;
            width: 300px;
            margin: 20px auto;
        }

        .bubble3 {
            position: relative;
            background-color: #3498db;
            color: #fff;
            border-radius: 15px;
            padding: 10px 15px;
            font-family: Arial, sans-serif;
        }

        .progress-bar3 {
            flex: 1;
            height: 25px;
            background-color: #f1c40f;
            border-radius: 10px;
            margin-left: 10px;
            overflow: hidden;
        }

        .progress3 {
            width: 50%;
            height: 100%;
            background-color: #e67e22;
            text-align: center;
        }

</style>
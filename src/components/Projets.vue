<template>
   <section>
    <h2>Mes Projets</h2>
    <p id="sous-titre">Cliquez sur les images pour plus de renseignement !</p>
    
    <ul>
        <li v-for="project in Tableau" :key="project.id">
        <h3>{{ project.title }}</h3>
    <button @click="openModal(project)"><img :src="project.img" alt="Image de mes projets"></button>
<Modal :isOpen="validBool"> 
    
    <template #header>
        <button class="btn-close" @click="closeModal">X</button>
        <h3>{{ info1.title }}</h3>
    </template>
    <template #body>
        <img :src="info1.img" alt="Image de mes projets" class="image">
        <p>{{ info1.techno }}</p>
        <p>{{ info1.lien }}</p>
        <p>{{ info1.Page }}</p>
    </template>
    <template #footer></template>
</Modal></li>
    </ul>
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

ul {
    display: flex;
    justify-content: space-around;
}


li {
    background-color: rgba(100, 224, 224, 0.638);
    border-radius: 50px;
    padding: 10px;
    margin: 10px;
    display: flex;
    justify-content: center;
    flex-direction: column;
    opacity: 0.7;
}
li:hover {
    opacity: 1;
    transition: 0.3s;
    box-shadow: 5px 5px 15px 5px #000000; 
    box-shadow: 5px 5px 15px 5px #000000;
}
h2 {
    font-size: 1.9rem;
}
#sous-titre{
    font-size: 1.4rem;
    text-decoration: underline;
}

img {
    width: 350px;
    height: 380px;
    border-radius: 15px;
}
.image {
    width: 350px;
    height: 380px;
    border-radius: 15px;
    transition: 1s;
    overflow: visible;
    
}
.image:hover {
    transform: scale(1.5);
}
button {
    font-size: 1.2rem;
    border-radius: 35px;
    cursor: pointer;
    
}
.btn-close {
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 50px;
    background-color: red;
    opacity: 0.8;
    transition: 0.7s;
}
.btn-close:hover {
    opacity: 1;
    width: 55px;
}



</style>


<script setup>
import {dataBase} from '@/stores/data'
import Modal from './Modal.vue';
import {onClickOutside} from '@vueuse/core'
import { onMounted , ref } from 'vue';

const info = ref(dataBase)
const info1 = ref(info.value[0])
const Tableau = ref([])
const paramClose = ref(null)
const validBool = ref(false)

onMounted (()=>{
    Tableau.value = dataBase
    
    onClickOutside(paramClose, closeModal)

})

const openModal = (project)=>{
    info1.value = project
    validBool.value = true
}
const closeModal = ()=>{
    validBool.value = false
}

</script>


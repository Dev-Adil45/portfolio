<script setup>
const props = defineProps ({isOpen:Boolean})

</script>

<template>
   <div v-if="props.isOpen" class="modal">
   <div class="modal-wrapper">
    <div class="modal-content">
    <slot name="header"></slot>
    <slot name="body"></slot>
    <slot name="footer"></slot>

   </div>
   </div>
   </div>
</template>

<style scoped>
.modal {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
}

.modal-wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  
}

.modal-content {
  background-color: #6c116cb5;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.33);
  width: 50%;
  max-width: 800px;
  padding: 20px 30px;
  color: antiquewhite;
  transition: 1s;
}
.modal-content:hover {
    transform: scale(1.2);
}
</style>

  
  
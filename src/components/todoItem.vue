<template>
  <div class="todoWrapper">
    <button class="removeTodo" @click="removeTodo">remove</button>
    {{todo.text}}
  </div>
</template>

<script src="./todoItem.js"></script>
<style src="./todoItem.css"></style>

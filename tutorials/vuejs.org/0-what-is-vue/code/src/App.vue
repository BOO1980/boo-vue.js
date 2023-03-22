<template>
<div id="app">
  <button @click="count++">
    Count is: {{ count }}
  </button>
</div>
  </template>
  
  <script>
  export default {
      data() {
        return {
        count: 0
      }
    }
  };
  </script>
  
  <style>
  #app {
    font-size: 18px;
    font-family: 'Roboto', sans-serif;
    color: blue;
  }
  </style>
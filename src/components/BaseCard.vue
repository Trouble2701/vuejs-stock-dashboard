<template>
    <div class="base-card">
      <slot></slot>
    </div>
  </template>
  
  <script>
  export default {
    name: 'BaseCard',
  };
  </script>
  
  <style scoped>
  .base-card {
    background-color: rgba(1, 31, 53, 1);
    padding: 20px 32px;
    border-radius: 16px;
  }
  </style>
  
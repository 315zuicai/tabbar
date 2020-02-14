<template>
  <div id="tab-bar">
    <slot></slot>
  </div>
</template>

<script>
  export default {

  }
</script>

<style>
  #tab-bar {
    display: flex;
    background-color: #f6f6f6;  

    position: fixed;
    bottom: 0px;
    left: 0px;
    right: 0px;

    box-shadow: 0px -1px 2px rgba(150, 150, 150, 0.8)
  }

</style>
<template>
    <div class="imac">
      <div class="div-2">
        <Overlap />
        <img class="vector" alt="Vector" src="/img/vector-1.svg" />
        <Group />
        <div class="text-wrapper-9">Top level</div>
        <div class="text-wrapper-10">About</div>
        <div class="text-wrapper-11">Works</div>
        <div class="text-wrapper-12">Contacts</div>
      </div>
    </div>
  </template>
  
  <script>
  import Overlap from "./Imac/sections/Overlap.vue";
  import Group from "./Imac/sections/Group.vue";
  
  export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: "Imac",
    components: {
      Overlap,
      Group,
    },
  };
  </script>
  
  <style>
  .imac {
    background-color: #000000;
    display: flex;
    flex-direction: row;
    justify-content: center;
    width: 100%;
  }
  
  .imac .div-2 {
    background-color: #000000;
    height: 720px;
    position: relative;
    width: 1280px;
  }
  
  .imac .vector {
    height: 38px;
    left: 68px;
    position: absolute;
    top: 44px;
    width: 44px;
  }
  
  .imac .text-wrapper-9 {
    color: #1e1e1e;
    font-family: "Jost", Helvetica;
    font-size: 12px;
    font-weight: 700;
    left: 1159px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 281px;
  }
  
  .imac .text-wrapper-10 {
    color: #43424880;
    font-family: "Jost", Helvetica;
    font-size: 12px;
    font-weight: 700;
    left: 1159px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 358px;
  }
  
  .imac .text-wrapper-11 {
    color: #77320f;
    font-family: "Jost", Helvetica;
    font-size: 12px;
    font-weight: 700;
    left: 1159px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 319px;
  }
  
  .imac .text-wrapper-12 {
    color: #43424880;
    font-family: "Jost", Helvetica;
    font-size: 12px;
    font-weight: 700;
    left: 1159px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 399px;
  }
  </style>
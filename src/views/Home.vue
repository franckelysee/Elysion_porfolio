<template>
    <div class="imac">
      <div class="overlap-wrapper">
        <div class="overlap">
          <div class="overlap-group">
            <img class="unsplash" alt="Unsplash" src="/src/assets/static/img/unsplash-wh3dddkxpoq.png" />
            <div class="text-wrapper">I’am</div>
            <div class="div">Umar</div>
            <div class="text-wrapper-2">Contact me</div>
            <p class="umarusmansnok-gmail">
              <span class="span">@umarusmansnok</span>
              <span class="text-wrapper-3">@</span>
              <span class="span">gmail.com</span>
            </p>
          </div>
          <img class="vector" alt="Vector" src="/src/assets/static/img/vector-1.svg" />
          <img class="line" alt="Line" src="/src/assets/static/img/line-18.svg" />
          <img class="img" alt="Line" src="/src/assets/static/img/line-26.svg" />
          <div class="text-wrapper-4">My work</div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
    export default {
        // eslint-disable-next-line vue/multi-word-component-names
        name: "Imac",
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
  
  .imac .overlap-wrapper {
    background-color: #000000;
    height: 720px;
    width: 1280px;
  }
  
  .imac .overlap {
    height: 720px;
    left: 61px;
    position: relative;
    width: 1175px;
  }
  
  .imac .overlap-group {
    height: 720px;
    left: 0;
    position: absolute;
    top: 0;
    width: 1175px;
  }
  
  .imac .unsplash {
    height: 720px;
    left: 508px;
    object-fit: cover;
    position: absolute;
    top: 0;
    width: 603px;
  }
  
  .imac .text-wrapper {
    color: #1e1e1e;
    font-family: "Poppins-Bold", Helvetica;
    font-size: 106.6px;
    font-weight: 700;
    left: 0;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 224px;
    width: 381px;
  }
  
  .imac .div {
    color: #ffffff;
    font-family: "Poppins-Bold", Helvetica;
    font-size: 106.6px;
    font-weight: 700;
    left: 0;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 328px;
    white-space: nowrap;
    width: 605px;
  }
  
  .imac .text-wrapper-2 {
    color: #77320f;
    font-family: "Poppins-Bold", Helvetica;
    font-size: 10px;
    font-weight: 700;
    left: 1060px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 28px;
  }
  
  .imac .umarusmansnok-gmail {
    color: transparent;
    font-family: "Poppins-Bold", Helvetica;
    font-size: 10px;
    font-weight: 700;
    left: 1007px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 43px;
  }
  
  .imac .span {
    color: #ffffff;
  }
  
  .imac .text-wrapper-3 {
    color: #77320f;
  }
  
  .imac .vector {
    height: 38px;
    left: 7px;
    position: absolute;
    top: 44px;
    width: 44px;
  }
  
  .imac .line {
    height: 25px;
    left: 14px;
    object-fit: cover;
    position: absolute;
    top: 494px;
    width: 1px;
  }
  
  .imac .img {
    height: 25px;
    left: 88px;
    object-fit: cover;
    position: absolute;
    top: 494px;
    width: 1px;
  }
  
  .imac .text-wrapper-4 {
    color: #ffffff;
    font-family: "Poppins-Bold", Helvetica;
    font-size: 12px;
    font-weight: 700;
    left: 24px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 496px;
  }
  </style>
  
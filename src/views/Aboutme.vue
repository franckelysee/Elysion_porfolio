<!-- eslint-disable vue/multi-word-component-names -->
<template>
    <div class="imac">
      <div class="div">
        <div class="overlap">
          <img class="unsplash" alt="Unsplash" src="/img/unsplash-wh3dddkxpoq.png" />
          <div class="text-wrapper">Top level</div>
          <div class="text-wrapper-2">Work</div>
          <div class="text-wrapper-3">About</div>
          <div class="text-wrapper-4">Contacts</div>
        </div>
        <img class="vector" alt="Vector" src="/img/vector-1.svg" />
        <div class="overlap-group">
          <div class="rectangle" />
          <div class="text-wrapper-5">Contact me</div>
        </div>
        <div class="overlap-2">
          <div class="rectangle-2" />
          <div class="text-wrapper-6">About me</div>
          <div class="text-wrapper-7">Download CV</div>
        </div>
        <p class="i-i-m-dejan-i-m-a">
          i, I’m Dejan. I'm a multi-talented human with over 10+ years of experiences in wide range of design disciplines.
          <br /> <br />
          You can also call me a product designer, experience designer, interaction, UI, UX or by any other market defined
          function-title. I'm also a multi-disciplinary maker with over 10 years of experiences in wide range of design
          disciplines, manager, advisor, entrepreneur, front-end developer, music enthusiast, traveler, photographer and
          more.
        </p>
        <div class="group">
          <div class="group-2">
            <div class="overlap-group-2">
              <div class="rectangle-3" />
              <img class="line" alt="Line" src="/img/line-4.svg" />
            </div>
            <div class="overlap-3">
              <div class="rectangle-4" />
              <img class="img" alt="Line" src="/img/line-5.svg" />
              <img class="line-2" alt="Line" src="/img/line-6.svg" />
              <div class="rectangle-5" />
              <img class="rectangle-6" alt="Rectangle" src="/img/rectangle-17.svg" />
            </div>
            <div class="rectangle-7" />
          </div>
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
  
  .imac .div {
    background-color: #000000;
    height: 720px;
    position: relative;
    width: 1280px;
  }
  
  .imac .overlap {
    height: 720px;
    left: 569px;
    position: absolute;
    top: 0;
    width: 640px;
  }
  
  .imac .unsplash {
    height: 720px;
    left: 0;
    object-fit: cover;
    position: absolute;
    top: 0;
    width: 603px;
  }
  
  .imac .text-wrapper {
    color: #43424880;
    font-family: "Jost", Helvetica;
    font-size: 12px;
    font-weight: 700;
    left: 590px;
    letter-spacing: 0;
    line-height: normal;
    opacity: 0.4;
    position: absolute;
    top: 281px;
  }
  
  .imac .text-wrapper-2 {
    color: #43424880;
    font-family: "Jost", Helvetica;
    font-size: 12px;
    font-weight: 700;
    left: 590px;
    letter-spacing: 0;
    line-height: normal;
    opacity: 0.4;
    position: absolute;
    top: 319px;
  }
  
  .imac .text-wrapper-3 {
    color: #77320f;
    font-family: "Jost", Helvetica;
    font-size: 12px;
    font-weight: 700;
    left: 590px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 359px;
  }
  
  .imac .text-wrapper-4 {
    color: #43424880;
    font-family: "Jost", Helvetica;
    font-size: 12px;
    font-weight: 700;
    left: 590px;
    letter-spacing: 0;
    line-height: normal;
    opacity: 0.4;
    position: absolute;
    top: 399px;
  }
  
  .imac .vector {
    height: 38px;
    left: 68px;
    position: absolute;
    top: 44px;
    width: 44px;
  }
  
  .imac .overlap-group {
    border-radius: 5px;
    height: 26px;
    left: 165px;
    position: absolute;
    top: 549px;
    width: 100px;
  }
  
  .imac .rectangle {
    background-color: #ffffff;
    border-radius: 5px;
    height: 26px;
    left: 0;
    position: absolute;
    top: 0;
    width: 100px;
  }
  
  .imac .text-wrapper-5 {
    color: #77320f;
    font-family: "Jost", Helvetica;
    font-size: 11px;
    font-weight: 700;
    left: 21px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 4px;
  }
  
  .imac .overlap-2 {
    height: 91px;
    left: 160px;
    position: absolute;
    top: 235px;
    width: 363px;
  }
  
  .imac .rectangle-2 {
    background-color: #ffffff;
    height: 17px;
    left: 5px;
    position: absolute;
    top: 74px;
    width: 74px;
  }
  
  .imac .text-wrapper-6 {
    color: #ffffff;
    font-family: "Poppins", Helvetica;
    font-size: 48px;
    font-weight: 700;
    left: 0;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 0;
    width: 363px;
  }
  
  .imac .text-wrapper-7 {
    color: #77320f;
    font-family: "Jost", Helvetica;
    font-size: 11px;
    font-weight: 700;
    left: 84px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 74px;
  }
  
  .imac .i-i-m-dejan-i-m-a {
    color: #ffffff;
    font-family: "Poppins", Helvetica;
    font-size: 12px;
    font-weight: 700;
    left: 161px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 354px;
    width: 377px;
  }
  
  .imac .group {
    height: 130px;
    left: 1222px;
    position: absolute;
    top: 283px;
    width: 21px;
  }
  
  .imac .group-2 {
    height: 130px;
    position: relative;
  }
  
  .imac .overlap-group-2 {
    height: 37px;
    left: 3px;
    position: absolute;
    top: 0;
    width: 15px;
  }
  
  .imac .rectangle-3 {
    border: 2px solid;
    border-color: #ffffff;
    border-radius: 27px;
    height: 15px;
    left: 0;
    position: absolute;
    top: 0;
    width: 15px;
  }
  
  .imac .line {
    height: 22px;
    left: 7px;
    position: absolute;
    top: 15px;
    width: 2px;
  }
  
  .imac .overlap-3 {
    height: 76px;
    left: 0;
    position: absolute;
    top: 54px;
    width: 21px;
  }
  
  .imac .rectangle-4 {
    border: 2px solid;
    border-color: #ffffff;
    border-radius: 27px;
    height: 15px;
    left: 3px;
    position: absolute;
    top: 61px;
    width: 15px;
  }
  
  .imac .img {
    height: 22px;
    left: 10px;
    position: absolute;
    top: 0;
    width: 2px;
  }
  
  .imac .line-2 {
    height: 22px;
    left: 10px;
    position: absolute;
    top: 40px;
    width: 2px;
  }
  
  .imac .rectangle-5 {
    background-color: #77320f;
    height: 8px;
    left: 7px;
    position: absolute;
    top: 27px;
    transform: rotate(-45deg);
    width: 8px;
  }
  
  .imac .rectangle-6 {
    height: 21px;
    left: 0;
    position: absolute;
    top: 20px;
    width: 21px;
  }
  
  .imac .rectangle-7 {
    border: 2px solid;
    border-color: #ffffff;
    height: 15px;
    left: 3px;
    position: absolute;
    top: 38px;
    transform: rotate(-45deg);
    width: 15px;
  }
  </style>
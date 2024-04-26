
<template>
    <div class="imac">
      <div class="div">
        <div class="overlap">
          <img class="unsplash" alt="Unsplash" src="/img/unsplash-wh3dddkxpoq.png" />
          <div class="text-wrapper">Top level</div>
          <div class="text-wrapper-2">About</div>
          <div class="text-wrapper-3">Works</div>
          <div class="text-wrapper-4">Contacts</div>
        </div>
        <img class="vector" alt="Vector" src="/img/vector-1.svg" />
        <div class="overlap-group">
          <div class="group">
            <div class="group-2">
              <div class="overlap-2">
                <div class="rectangle" />
                <img class="line" alt="Line" src="/img/line-4.svg" />
              </div>
              <div class="overlap-group-2">
                <div class="rectangle-2" />
                <img class="img" alt="Line" src="/img/line-5.svg" />
                <img class="line-2" alt="Line" src="/img/line-6.svg" />
                <img class="rectangle-3" alt="Rectangle" src="/img/rectangle-17.svg" />
              </div>
              <div class="rectangle-4" />
            </div>
          </div>
          <div class="ellipse" />
        </div>
        <div class="rectangle-5" />
        <div class="text-wrapper-5">Say Hello!</div>
        <div class="text-wrapper-6">Write an Email</div>
        <div class="overlap-3">
          <div class="rectangle-6" />
          <div class="text-wrapper-7">ENTER YOUR NAME*</div>
        </div>
        <div class="div-wrapper">
          <div class="text-wrapper-8">ENTER YOUR EMAIL*</div>
        </div>
        <div class="overlap-4">
          <div class="rectangle-6" />
          <div class="text-wrapper-9">PHONE NUMBER</div>
        </div>
        <div class="text-wrapper-10">SUBMIT</div>
        <img class="line-3" alt="Line" src="/img/line-17.svg" />
        <img class="line-4" alt="Line" src="/img/line-18.svg" />
      </div>
    </div>
  </template>
  
  <script setup>
   
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
    color: #ffffff;
    font-family: "Jost", Helvetica;
    font-size: 12px;
    font-weight: 700;
    left: 590px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 281px;
  }
  
  .imac .text-wrapper-2 {
    color: #ffffff;
    font-family: "Jost", Helvetica;
    font-size: 12px;
    font-weight: 700;
    left: 590px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 359px;
  }
  
  .imac .text-wrapper-3 {
    color: #ffffff;
    font-family: "Jost", Helvetica;
    font-size: 12px;
    font-weight: 700;
    left: 590px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 319px;
  }
  
  .imac .text-wrapper-4 {
    color: #77320f;
    font-family: "Jost", Helvetica;
    font-size: 12px;
    font-weight: 700;
    left: 590px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 394px;
  }
  
  .imac .vector {
    height: 38px;
    left: 68px;
    position: absolute;
    top: 44px;
    width: 44px;
  }
  
  .imac .overlap-group {
    height: 129px;
    left: 1222px;
    position: absolute;
    top: 283px;
    width: 21px;
  }
  
  .imac .group {
    height: 129px;
    left: 0;
    position: absolute;
    top: 0;
    width: 21px;
  }
  
  .imac .group-2 {
    height: 129px;
    position: relative;
  }
  
  .imac .overlap-2 {
    height: 37px;
    left: 3px;
    position: absolute;
    top: 0;
    width: 15px;
  }
  
  .imac .rectangle {
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
  
  .imac .overlap-group-2 {
    height: 75px;
    left: 0;
    position: absolute;
    top: 54px;
    width: 21px;
  }
  
  .imac .rectangle-2 {
    border: 2px solid;
    border-color: #ffffff;
    border-radius: 27px;
    height: 15px;
    left: 3px;
    position: absolute;
    top: 60px;
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
  
  .imac .rectangle-3 {
    height: 21px;
    left: 0;
    position: absolute;
    top: 20px;
    width: 21px;
  }
  
  .imac .rectangle-4 {
    border: 2px solid;
    border-color: #ffffff;
    height: 15px;
    left: 3px;
    position: absolute;
    top: 38px;
    transform: rotate(-45deg);
    width: 15px;
  }
  
  .imac .ellipse {
    background-color: #77320f;
    border-radius: 3.5px;
    height: 7px;
    left: 7px;
    position: absolute;
    top: 118px;
    width: 7px;
  }
  
  .imac .rectangle-5 {
    background-color: #ffffff;
    height: 17px;
    left: 73px;
    position: absolute;
    top: 253px;
    width: 74px;
  }
  
  .imac .text-wrapper-5 {
    color: #ffffff;
    font-family: "Poppins", Helvetica;
    font-size: 48px;
    font-weight: 700;
    left: 68px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 153px;
    width: 434px;
  }
  
  .imac .text-wrapper-6 {
    color: #77320f;
    font-family: "Jost", Helvetica;
    font-size: 24px;
    font-weight: 700;
    left: 155px;
    letter-spacing: 0;
    line-height: normal;
    position: absolute;
    top: 243px;
  }
  
  .imac .overlap-3 {
    height: 46px;
    left: 70px;
    position: absolute;
    top: 313px;
    width: 420px;
  }
  
  .imac .rectangle-6 {
    border: 1px solid;
    border-color: transparent;
    border-image: linear-gradient(to bottom, rgb(119, 50.24, 15.87), rgba(255, 255, 255, 0.47)) 1;
    border-radius: 7px;
    height: 36px;
    left: 0;
    position: absolute;
    top: 6px;
    width: 420px;
  }
  
  .imac .text-wrapper-7 {
    color: #8b8b8b;
    font-family: "Montserrat", Helvetica;
    font-size: 10px;
    font-weight: 700;
    height: 46px;
    left: 10px;
    letter-spacing: 0.4px;
    line-height: normal;
    position: absolute;
    top: 0;
    width: 205px;
  }
  
  .imac .div-wrapper {
    border-radius: 7px;
    height: 36px;
    left: 70px;
    position: absolute;
    top: 379px;
    width: 420px;
  }
  
  .imac .text-wrapper-8 {
    color: #8b8b8b;
    font-family: "Montserrat", Helvetica;
    font-size: 10px;
    font-weight: 700;
    height: 21px;
    left: 10px;
    letter-spacing: 0.4px;
    line-height: normal;
    position: absolute;
    top: 7px;
    width: 205px;
  }
  
  .imac .overlap-4 {
    height: 45px;
    left: 70px;
    position: absolute;
    top: 433px;
    width: 420px;
  }
  
  .imac .text-wrapper-9 {
    color: #8b8b8b;
    font-family: "Montserrat", Helvetica;
    font-size: 10px;
    font-weight: 700;
    height: 45px;
    left: 10px;
    letter-spacing: 0.4px;
    line-height: normal;
    position: absolute;
    top: 0;
    width: 206px;
  }
  
  .imac .text-wrapper-10 {
    color: #ffffff;
    font-family: "Montserrat", Helvetica;
    font-size: 16px;
    font-weight: 700;
    height: 45px;
    left: 241px;
    letter-spacing: 1.6px;
    line-height: normal;
    position: absolute;
    text-align: center;
    top: 517px;
    width: 76px;
  }
  
  .imac .line-3 {
    height: 32px;
    left: 353px;
    position: absolute;
    top: 525px;
    width: 3px;
  }
  
  .imac .line-4 {
    height: 32px;
    left: 204px;
    position: absolute;
    top: 525px;
    width: 3px;
  }
  </style>
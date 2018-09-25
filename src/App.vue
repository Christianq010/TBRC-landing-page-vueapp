<template>
  <div id="app">
    <div id="nav">
      <router-link to="/"></router-link>
      <!-- <router-link to="/about">About</router-link> -->
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">
@charset "UTF-8";

// font imports
@font-face {
  font-family: AvenirNextReg;
  src: url("./assets/fonts/AvenirNext-Regular.ttf") format("truetype");
}
@font-face {
  font-family: AvenirNextBold;
  src: url("./assets/fonts/AvenirNext-Bold.ttf") format("truetype");
}
@font-face {
  font-family: HelveticaNeueUltraLight;
  src: url("./assets/fonts/HelveticaUltraLt.ttf") format("typetype");
}
@font-face {
  font-family: HelveticaNeueLight;
  src: url("./assets/fonts/HelveticaNeue-Light.otf") format("opentype");
}
@font-face {
  font-family: HelveticaNeue;
  src: url("./assets/fonts/HELVETICA.TTF") format("truetype");
}
@font-face {
  font-family: HelveticaNeueBold;
  src: url("./assets/fonts/HELVETICA-BOLD.TTF") format("truetype");
}

@import "@/scss/base.scss";
html {
  box-sizing: border-box;
}
*,
*:before,
*:after {
  box-sizing: inherit;
}
body {
  font-family: "AvenirNextReg", "HelveticaNeue", Arial, sans-serif;
  margin: 0px;
  padding: 0px;
}
a:hover {
  cursor: pointer;
}
</style>

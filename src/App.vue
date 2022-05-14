<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
@import "~@/assets/style/helper.scss";
@import "~@/assets/style/reset.scss";

body {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-family: $font-kai;
  font-size: 16px;
  line-height: 1.5;
  color: #2c3e50;
}
.clearfix::after{
  content: "";
  display: block;
  clear: both;
}
</style>

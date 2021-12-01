<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@100;300;400;500;600;700;900&display=swap");
.body {
  background: #101010;
  min-height: 100vh;
  font-family: "Poppins", sans-serif;
}
.home {
  overflow: hidden;
}
.title {
  font-size: 58px;
}
.abouttrio-title {
  font-size: 18px;
}
.planet-title {
  font-size: 28px;
}
.sm-title {
  font-size: 48px;
}
.xs-title {
  font-size: 36px;
}

@media (max-width: 767.98px) {
  .title,
  .sm-title,
  .xs-title {
    font-size: 36px;
  }
  .planet-title {
    font-size: 20px;
  }
}
</style>

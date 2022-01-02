<template>
   <div class="my-navbar">
      <span  class="font-weight-bold my-navbar__logo">
      <router-link to="/">
        <img  src="@/assets/bancc.png" width="240">

      </router-link>
      </span>
    <Slide right>
      <router-link to="/">
        <img src="@/assets/bancc.png" width="250"  >

      </router-link>
          <router-link style="text-decoration: none; color: inherit;" to="/">🏠 HOME </router-link>
          <router-link style="text-decoration: none; color: inherit;" to="/faq">❓ FAQ </router-link>
          <router-link style="text-decoration: none; color: inherit;" to="/about">ℹ️ ABOUT </router-link>
          <a href="https://doc.bancc.io/documentation/" style="text-decoration: none; color: #009245;">⚛️ DOCUMENTATION </a>
          <a href="https://doc.bancc.io/documentation/v/whitepaper/" style="text-decoration: none; color: #009245;"> 📖 WHITEPAPER </a>
          <a href="https://doc.bancc.io/documentation/v/launch/" style="text-decoration: none; color: #009245;">🚀 LAUNCH </a>
          <a href="https://bancc.io/pitch/" style="text-decoration: none; color: #009245;">📔 PITCHDECK </a>
          <br>
          
          <div class="blink_me">
            <a href="https://refer.bancc.io" target="_blank" rel="noopener noreferrer" style="text-decoration: none; color: #009245;" >
              <h4>
                JOIN THE WHITELIST TODAY!
                <br>
                EARN 10$ FOR EACH FRIEND YOU REFER!
                <br>
                50% COMISSION - 3 LEVEL SYSTEM
              </h4>
              </a>
          </div>
          <b-dropdown id="dropdown-offset" offset=""  text="APPLY FOR WHITELIST" variant="success"  class="m-2">
              <b-dropdown-item href="https://www.bancc.io/refer" target="_blank">Apply for Whitelist</b-dropdown-item>
              <b-dropdown-item href="https://doc.bancc.io/documentation/v/launch/competitions/refer-a-friend" target="_blank">Information</b-dropdown-item>
              <b-dropdown-item href="https://doc.bancc.io/documentation/v/launch/competitions/rules" target="_blank">Rules</b-dropdown-item>
              <b-dropdown-item href="https://doc.bancc.io/documentation/v/launch/competitions" target="_blank">Competitions</b-dropdown-item>
          </b-dropdown> 
    </Slide>   
  </div>
</template>

<script>

import { Slide } from "vue-burger-menu";

export default {
  name: "App",
  components: { 
     Slide,
  }
};

</script>

<style lang="scss">
.my-navbar {
  color: #fff;
  display: flex;
  align-items: center;
  &__logo {
    display:flex;
    text-transform: uppercase;
    letter-spacing: 2px;
    position: absolute;
    left: 25%;
    top: 5%;
    transform: translate(-35%, -35%);
    margin: 0;
  }
  &__items {
    display: flex;
    align-items: center;
    margin-top: 10px;
  }
  &__item {
    padding: 15px 20px;
  }
  &__link {
    display: flex;
    align-items: center;
    justify-content: center;
    color: #fff;
    text-decoration: none;
  }
  
}
.bm-burger-button {
      position: absolute;
      width: 36px;
      height: 30px;
      left: 36px;
      top: 36px;
      cursor: pointer;
    }
    .bm-burger-bars {
      background-color: #ffffff;
    }
    .line-style {
      position: absolute;
      height: 20%;
      left: 0;
      right: 0;
    }
    .cross-style {
      position: absolute;
      top: 12px;
      right: 2px;
      cursor: pointer;
    }
    .bm-cross {
      background: #ffffff;
    }
    .bm-cross-button {
      height: 36px;
      width: 36px;
    }
    .bm-menu {
      height: 100%; /* 100% Full-height */
      width: 0; /* 0 width - change this with JavaScript */
      position: fixed; /* Stay in place */
      z-index: 1000; /* Stay on top */
      top: 0;
      left: 0;
      background-color: rgb(0, 0, 0); /* Black*/
      overflow-x: hidden; /* Disable horizontal scroll */
      padding-top: 30px; /* Place content 60px from the top */
      transition: 0.5s; /*0.5 second transition effect to slide in the sidenav*/
    }

    .bm-overlay {
      background: #101010;
    }
    .bm-item-list {
      color: #ffffff;
      margin-left: 10%;
      font-size: 20px;
    }
    .bm-item-list > * {
      display: flex;
      text-decoration: none;
      padding: 0.7em;
    }
    .bm-item-list > * > span {
      margin-left: 10px;
      font-weight: 700;
      color: rgb(170, 14, 14);
    }

    .blink_me {
  animation: blinker 2s linear infinite;
  
}

@keyframes blinker {
  50% {
    opacity: 0;
  }
}


</style>

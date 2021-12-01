<template>
  <b-container>
    <div class="my-navbar">
      <span  class="font-weight-bold my-navbar__logo">
      <router-link to="/">
        <img  src="@/assets/bancc.png" width="120">

      </router-link>
      </span>
      <div class="my-navbar__items mx-auto">
        <div class="my-navbar__item">
          <router-link to="/" class="my-navbar__link"> BANCC </router-link>
        </div>
        <div class="my-navbar__item">
          <router-link to="/faq" class="my-navbar__link"> FAQs </router-link>
        </div>
        <div class="my-navbar__item">
          <router-link to="/about" class="my-navbar__link"> ABOUT </router-link>
        </div>
      </div>
    </div>
  </b-container>
</template>

<script>
export default {
  name: "navbar",
};
</script>

<style lang="scss">
.my-navbar {
  color: #fff;
  display: flex;
  align-items: center;
  &__logo {
    text-transform: uppercase;
    letter-spacing: 2px;
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
</style>

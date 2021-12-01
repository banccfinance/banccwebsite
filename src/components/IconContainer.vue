<template>
  <div class="icon-container">
    <div class="icon-container__icon-wrapper">
      <i class="icon-container__icon" :class="icon ? icon : ''"></i>
    </div>
    <h4 class="icon-container__title mb-1">
      {{ title ? title : "Lorem Ipsum." }}
    </h4>
    <h6 class="icon-container__description">
      {{ desc ? desc : "Lorem Ipsum." }}
    </h6>
  </div>
</template>

<script>
export default {
  props: ["icon", "title", "desc"],
};
</script>

<style lang="scss">
.icon-container {
  color: #fff;
  &__icon {
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 32px;
    text-shadow: 0 0 50px#009149;
    color: #009149;
    &-wrapper {
      width: 75px;
      height: 75px;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 20px;
      border-radius: 10px;
      background: #171717;
    }
  }
  &__description {
    font-weight: 300;
    max-width: 80%;
    @media (max-width: 991.98px) {
      max-width: 100%;
    }
  }
}
</style>

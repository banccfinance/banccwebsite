<template>
  <button class="button" :class="{ 'button--link': isLink, 'p-0': noPadding }">
    <span v-if="value">{{ value }}</span
    ><span v-else>Lorem Ipsum</span>
    <i
      class="ml-2 mt-1"
      :class="icon ? icon : 'fa fa-long-arrow-alt-right'"
    ></i>
  </button>
</template>

<script>
export default {
  name: "theme-button",
  props: ["isLink", "noPadding", "value", "icon"],
};
</script>

<style lang="scss">
.button {
  background: #fff;
  border: 0;
  border-radius: 12.5px;
  padding: 12px 32px;
  font-weight: 600;
  display: inline-flex;
  align-items: center;
  &--link {
    background: transparent;
    color: #fff;
  }
}
</style>

<template>
  <div class="section-2">
    <b-container>
      <h1 class="section-2__title title">
        BANCC brings value <br />to our investors.
      </h1>
      <h5 class="section-2__paragraph mt-4">
        The idea of bringing value to investors has always been one of our key
        focuses, we do that by brining real world usage of our $BANC coin -
        Helping to increase the price based on usage!
      </h5>
      <div
        class="
          mt-4 mt-md-0
          d-block
          text-center
          d-md-flex
          align-items-center
          justify-content-center
        "
      > 
      <a href="https://doc.bancc.io" target="_blank" rel="noopener noreferrer">
        <Button class="my-0 my-md-4" value="Whitepaper" /> 
        </a>
        <a href="https://t.me/banccio" target="_blank" rel="noopener noreferrer">
        <Button
          class="my-0 my-md-4"
          :isLink="true"
          value="Join Telegram"
          icon="fab fa-telegram-plane"
        />
        </a>
      </div>
    </b-container>
  </div>
</template>

<script>
import IconContainer from "../IconContainer.vue";
import Button from "../Button.vue";
export default {
  components: { IconContainer, Button },
  name: "section-2",
};
</script>

<style lang="scss">
.section-2 {
  text-align: center;
  max-width: 50%;
  margin: 0 auto;

  &__title {
    color: #fff;
    text-transform: uppercase;
  }
  &__paragraph {
    color: #fff;
    font-weight: 200;
  }
  @media (max-width: 991.98px) {
    max-width: 80%;
  }
  @media (max-width: 767.98px) {
    max-width: 100%;
  }
}
</style>

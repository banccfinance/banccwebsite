<template>
  <div class="section-planet">
    <b-container>
      <!-- <h5 class="text-uppercase section-planet__sub-title">
        BANNC GIVES YOU CONTROL
      </h5> -->
      <h1 class="section-planet__title title">BANCC GIVES YOU CONTROL</h1>
      <p class="section-planet__title planet-title mt-4">
        Be your own payment processor
      </p>

      <p class="section-planet__title planet-title mt-4">
        Be your own remittance service
      </p>
      <p class="section-planet__title planet-title mt-4">
        Be your own marketplace
      </p>
      <p class="section-planet__title planet-title mt-4">
        Be your own debit card
      </p>
      <p class="section-planet__title planet-title mt-4">
        Be your own exchange
      </p>
      <p class="section-planet__title planet-title mt-4">Be your own BANCC.</p>
      

      <!-- <transition name="fade"> -->
      <!-- <p class="section-planet__title planet-title mt-4" v-if="show==0">
        Be your own payment processor</p>
    <p class="section-planet__title planet-title mt-4" v-else-if="show==1">
      Be your own remittance service
    </p>
    <p class="section-planet__title planet-title mt-4" v-else-if="show==2">
      Be your own marketplace
    </p>
    <p class="section-planet__title planet-title mt-4" v-else-if="show==3">
      Be your own debit card
    </p>
    <p class="section-planet__title planet-title mt-4" v-else-if="show==4">      
      Be your own exchange
    </p>
    <p class="section-planet__title planet-title mt-4" v-else-if="show==5">
      Be your own BANCC.
    </p> -->

      <!-- </transition> -->
    </b-container>
  </div>
</template>

<script>
import IconContainer from "../IconContainer.vue";
import Button from "../Button.vue";

export default {
  components: { IconContainer, Button },
  name: "section-planet",
  created() {
    setInterval(() => {
      if (this.show == 5) {
        this.show = 0;
      } else {
        this.show = this.show + 1;
      }
    }, 3000);
  },
  data() {
    return {
      msg: "msg",
      show: 0,
    };
  },
};
</script>

<style lang="scss">
.section-planet {
  // text-align: center;
  max-width: 70%;
  margin-left: 5%;

  &__title {
    color: #fff;
    text-transform: uppercase;
  }
  &__paragraph {
    color: #fff;
    font-weight: 200;
    font-size: 20px;
  }
  @media (max-width: 991.98px) {
    max-width: 80%;
  }
  @media (max-width: 767.98px) {
    max-width: 100%;
  }
}

.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s;
}
.fade-enter, .fade-leave-to /* .fade-leave-active below version 2.1.8 */ {
  opacity: 0;
}
</style>

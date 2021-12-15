<template>
  <div class="section-1">
    <b-container>
      <h5 class="text-uppercase section-1__sub-title">
        Forget your bank, go BANCC.
      </h5>
      <h1 class="section-1__title title">BANCC<br />FEATURES</h1>
      <div class="section-1__move-left">
        <h5 class="section-1__paragraph mt-4">
          The whole cryptomarket are expericing todays banking options are
          expensive and slow to use and leaving alot of people out of it. Being
          short for better alternatives, that's what we've been stuck with.
          Until now.
        </h5>
        <div class="section-1__icons">
          <b-row>
            <b-col md="6" class="mt-4">
              <icon-container
                title="Money transfer"
                desc="Send Money worldwide within 1 second using our easy to use app"
                icon="fas fa-paper-plane"
              />
            </b-col>
            <b-col md="6" class="mt-4">
              <icon-container
                title=" Finance & Trading"
                desc="Easily trade your favorite cryptocurrency with our easy to use app"
                icon="fas fa-chart-line"
              />
            </b-col>
            <b-col md="6" class="mt-4">
              <icon-container
                title="Debit cards"
                desc="Pay with your own BANCC debit card or pay directly with the cryptocurrency wallet. Your money, your choice"
                icon="fas fa-credit-card"
              />
            </b-col>
            <b-col md="6" class="mt-4">
              <icon-container
                title="Marketplace"
                desc="Setup your online store in a few clicks with the BANCC Marketplace"
                icon="fa fa-building"
              />
            </b-col>
          </b-row>
        </div>
        <a href="https://serv.bancc.io/signup" target="_blank" rel="noopener noreferrer">
        <Button  ass="my-4" value="JOIN THE LAUNCH" />
        </a>
      </div>
    </b-container>
  </div>
</template>

<script>
import IconContainer from "../IconContainer.vue";
import Button from "../Button.vue";

import icon1 from "../../assets/imgs/icon1.png";
import icon2 from "../../assets/imgs/icon2.png";
import icon3 from "../../assets/imgs/icon3.png";
import icon4 from "../../assets/imgs/icon4.png";
export default {
  components: { IconContainer, Button },
  name: "section-1",
  data() {
    return {
      icons: [icon1, icon2, icon3, icon4],
    };
  },
};
</script>

<style lang="scss">
.section-1 {
  letter-spacing: 1px;
  // margin-left: 30%;
  margin-left:5%;
  max-width: 60%;
  &__sub-title {
    color: #717271;
    margin-top: 85px;
  }
  &__move-left {
    margin-left: 110px;
    @media (max-width: 767.98px) {
      margin-left: 0;
    }
  }
  &__title {
    color: #fff;
    text-transform: uppercase;
  }
  &__paragraph {
    color: #fff;
    font-weight: 200;
  }
  @media (max-width: 991.98px) {
    margin-left: 15px;
  }
  @media (max-width: 767.98px) {
    margin-left: 0;
    max-width: 100%;
  }
}
</style>

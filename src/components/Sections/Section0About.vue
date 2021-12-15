<template>
  <div class="section-0about">
    <b-container>
      <h5 class="text-uppercase section-1__sub-title">
        Forget your bank, go BANCC.
      </h5>
      <h1 class="section-1__title title">About BANCC.</h1>
      <div class="section-1__move-left">
        <h5 class="section-1__paragraph mt-4">
          We're the reason Crypto will become mainstream. The faults of the
          payment industry is about to be a memory of the past. Its time for
          crypto to do what crypto was designed to do - solve real world
          problems. With our $BANCC coin and all the features that comes with it
          - we belive we are the future of the payment industry and we're
          inviting YOU on the journey. Join our launch starting 14th January 2022.
        </h5>
        <h5 class="section-1__paragraph mt-4">
          As the name states, you’ve probably already understod at least a
          little bit about what we do. BANCC is founded and has a vision to
          compete with regular banks in the following segments
        </h5>
        <h5 class="section-1__paragraph mt-4">
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
        </h5>

      </div>
      <img src="https://bancc.io/files/bancapptrio3.png" width="1000" align="right" />
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
  name: "section-0About",
  data() {
    return {
      icons: [icon1, icon2, icon3, icon4],
    };
  },
};
</script>

<style lang="scss">
.section-0about {
  letter-spacing: 1px;
  margin-left: 30%;
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
  }
  @media only screen and (max-width: 500px) {
    img {
       display: none;
    }
}
}
</style>
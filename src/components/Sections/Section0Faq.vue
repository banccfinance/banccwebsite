<template>
  <div class="section-0faq">
    <b-container>
      <h5 class="text-uppercase section-1__sub-title">
        Forget your bank, go BANCC.
      </h5>
      <h1 class="section-1__title title">
        Frequently asked <br />
        questions
      </h1>
      <div class="section-1__move-left">
        <h5 class="section-1__paragraph mt-4 fw-500">
          How can Bancc compete with Crypto.com, Binance etc?
        </h5>
        <h5 class="section-1__paragraph mt-4">
          The core idea behind every successful company is focusing on
          profitability of course. The main difference between Bancc and these
          companies is that these companies want to generate as high income as
          possible for their shareholders and their validators are seen as
          partners within their company strategy and revenue model. Bancc brings
          the same type of revenue model but for the “public” eye. Decreasing
          the total income for Bancc and increasing it for the participants in
          the blockchain.
        </h5>
      </div>

      <div class="section-1__move-left">
        <h5 class="section-1__paragraph mt-4 fw-500">
          How can Bancc do all of these things?
        </h5>
        <h5 class="section-1__paragraph mt-4">
          Technology is an interesting part of evolution and as we have seen
          with Bitcoin, especially the last decade. Things are starting to
          evolve at a greater pace than ever before. Bancc was founded on the
          belief that technology should be available for everyone and making it
          difficult for users to interact with is not the road we believe is
          right. By connecting existing technologies that have a previous
          history that shows stability and room for growth Bancc, will be able
          to bridge the gap between regular banking instruments and the
          cryptocurrency atmosphere.
        </h5>
      </div>

      <div class="section-1__move-left">
        <h5 class="section-1__paragraph mt-4 fw-500">Why is Bancc needed?</h5>
        <h5 class="section-1__paragraph mt-4">
          The world is changing and cryptocurrency is here to stay. Just one
          thing, fees. If you look at it in the general users that for example
          uses remittance services. Fees are somewhat the same thing. Nobody
          wants to work for free but charging high fees harms the potential
          growth of the network. Sending 10$ of worth should not be costing 60$
          at prime time. The general public will be needing something that is
          cost effective and easier to use then the current services provided
          today. Bancc solves this problem in a decentralised manner with
          creating a healthy and sustainable economy that does not rely on one
          single part, but the overall users in the network.
        </h5>
      </div>

      <div class="section-1__move-left">
        <h5 class="section-1__paragraph mt-4 fw-500">
          Want to take a deeper dive into the Bancc Blockchain?
        </h5>
        <a href="https://serv.bancc.io/signup" target="_blank" rel="noopener noreferrer">
        <Button class="my-4" value="JOIN THE LAUNCH" />
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
  name: "section-0Faq",
  data() {
    return {
      icons: [icon1, icon2, icon3, icon4],
    };
  },
};
</script>

<style lang="scss">
.section-0faq {
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
  .fw-500 {
    font-weight: 500;
  }
}
</style>

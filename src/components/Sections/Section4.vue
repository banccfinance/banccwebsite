<template>
  <div class="section-4">
    <b-container>
      <p class="text-uppercase section-4__sub-title">WHO ARE WE?</p>
      <h1 class="section-4__title title">BANCC</h1>
      <b-row class="align-items-center">
        <b-col md="12">
          <h5 class="d-flex section-4__card align-items-center">
            <h5 class="section-4__paragraph w-100 mw-100 mx-0 mt-4 mr-2">
              Bancc’s vision is to change the way we interact and transfer
              money with each other on a daily basis. The industry is currently
              in the process of a big paradigm shift and there is always new
              competition in the traditional market and cryptocurrency market,
              whose ideas are currently demanding better, faster and more secure
              solutions/services than ever before.
            </h5>

            <small class="section-4__card__info section-4__card__info--big"
              >BOOM,<br />BAM,<br />BANCC</small
            >
          </h5>
        </b-col>
        <b-col md="6" class="d-flex">
          <h5 class="section-4__card mt-4 mr-5">
            <p class="text-uppercase m-0 section-4__card__sub-title">
              ICO PRICE
            </p>
            <div class="d-flex align-items-center">
              <h1 class="m-0 section-4__card__title title">$0.004</h1>
            </div>
            <small class="section-4__card__info">3BN Starting supply</small>
          </h5>
        </b-col>
        <b-col md="6" class="d-flex justify-content-md-start">
          <a href="https://ico.bancc.io" target="_blank" rel="noopener noreferrer">
          <Button :value="'Join ICO'" />
          </a>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import IconContainer from "../IconContainer.vue";
import Button from "../Button.vue";
export default {
  components: { IconContainer, Button },
  name: "section-4",
};
</script>

<style lang="scss">
.section-4 {
  &__title {
    color: #fff;
    // font-size: 48px;
    text-transform: uppercase;
  }
  &__sub-title {
    color: #717271;
    letter-spacing: 1px;
    font-weight: 600;
  }
  &__paragraph {
    color: #fff;
    font-weight: 300;
    font-size: 16px;
    max-width: 60%;
    @media (max-width: 991.98px) {
      max-width: 80%;
    }
  }
  &__card {
    &__sub-title {
      color: #717271;
      letter-spacing: 1px;
      font-weight: 600;
      font-size: 14px;
    }
    &__title {
      color: #fff;
      font-size: 72px;
      font-weight: 700;
    }
    &__aside {
      color: #fff;
    }
    &__info {
      color: #fff;
      font-size: 12px;
      margin-top: -8px;
      display: block;
      &--big {
        font-size: 24px;
        font-weight: bold;
      }
    }
  }
}
</style>

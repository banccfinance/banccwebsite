<template>
  <div class="section-3">
    <b-container>
      <h1 class="section-3__title title">BANCC<br />BLOCKCHAIN</h1>
      <!-- <div class="d-flex align-items-center">
        <Button class="my-4" :noPadding="true" :isLink="true" />
      </div> -->
      <b-row class="my-5">
        <b-col lg="12" xl="5" class="mb-5 mb-xl-0">
          <div class="coming-soon-container">
            <p class="coming-soon-container__sub-title text-uppercase">
              Transactions
            </p>
            <h4
              class="
                sm-title
                coming-soon-container__title coming-soon-container__title--icon
              "
            >
              Send money worldwide with lightning speed!
            </h4>
            <img
              src="@/assets/imgs/icon2.png"
              class="coming-soon-container__icon"
            />
            <!-- <small class="coming-soon-container__tag">Coming Soon</small> -->
          </div>
        </b-col>
        <b-col lg="12" xl="7">
          <b-row>
            <b-col md="12">
              <div
                class="mb-5 coming-soon-container coming-soon-container--small"
              >
                <p class="coming-soon-container__sub-title text-uppercase">
                  Masternode
                </p>
                <img
                  src="@/assets/imgs/icon1.png"
                  class="
                    coming-soon-container__icon coming-soon-container__icon--1
                  "
                />
                <h4 class="sm-title coming-soon-container__title">
                  Earn $BANC-<br />by running <br />a BANCC
                  validator
                </h4>
                <!-- <small class="coming-soon-container__tag">Coming Soon</small> -->
              </div>
            </b-col>
            <b-col md="6">
              <div
                class="mb-5 coming-soon-container coming-soon-container--small"
              >
                <p class="coming-soon-container__sub-title text-uppercase">
                  Volume
                </p>
                <h4 class="xs-title coming-soon-container__title">
                  10,000 transactions per second 
                </h4>
                <!-- <small class="coming-soon-container__tag">Coming Soon</small> -->
              </div>
            </b-col>
            <b-col md="6">
              <div
                class="mb-5 coming-soon-container coming-soon-container--small"
              >
                <p class="coming-soon-container__sub-title text-uppercase">
                  CEFI & DEFI
                </p>
                <h4 class="xs-title coming-soon-container__title">
                  Your coins, your opportunites
                </h4>
                <!-- <small class="coming-soon-container__tag">Coming Soon</small> -->
              </div>
            </b-col>
          </b-row>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import Button from "../Button.vue";
export default {
  components: { Button },
  name: "section-3",
};
</script>

<style lang="scss">
.section-3 {
  &__title {
    color: #fff;
    text-transform: uppercase;
  }
}
.coming-soon-container {
  width: 100%;
  height: 550px;
  border-radius: 20px;
  background: #171717;
  padding: 20px 20px 60px;
  color: #fff;
  position: relative;
  &--small {
    height: 250px;
    @media (max-width: 1199.98px) {
      height: auto;
    }
  }
  &__sub-title {
    color: #717271;
    letter-spacing: 1px;
    font-weight: 600;
  }
  &__title {
    font-weight: 600;
    &--icon {
      padding: 200px 0 0;
      @media (max-width: 575.98px) {
        padding: 0;
      }
    }
  }
  &__tag {
    position: absolute;
    left: 20px;
    bottom: 20px;
    color: #8a8a8a;
  }
  &__icon {
    position: absolute;
    height: 490px;
    width: 490px;
    top: -90px;
    left: -170px;
    @media (max-width: 1199.98px) {
      left: -200px;
    }
    @media (max-width: 575.98px) {
      display: none;
    }
    &--1 {
      top: -160px;
      left: calc(100% - 310px);
    }
  }
  @media (max-width: 1199.98px) {
    height: auto;
  }
}
</style>

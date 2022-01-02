<template>

  <div class="section-1about">
    <b-container>
      <h5 class="text-uppercase section-1about__sub-title">
        Forget your bank, go BANCC.
      </h5>
      <h1 class="section-1about__title title">Why BANCC.</h1>
      <div class="section-1about__move-left">
        <h5 class="section-1about__paragraph mt-4">
          One of our main beliefs is that every Crypto coin/token should have
          utility. A lot of projects miss that part but we don’t. $BANCC will be
          used our platform to solve a real world problem and that’s what makes
          us different.
        </h5>
        <h5 class="section-1about__paragraph mt-4">
          From using $BANCC we can go:
        </h5>
        <b-row>
          <b-col md="4" cols="12">
            <div class="mb-5 about-trio-container about-trio-container--small">
              <p class="about-trio-container__sub-title text-uppercase">Fiat</p>
              <h4 class="abouttrio-title about-trio-container__title">
                User automatically buys Bancc.
              </h4>
            </div>
          </b-col>
          <b-col md="4" cols="12">
            <div class="mb-5 about-trio-container about-trio-container--small">
              <p class="about-trio-container__sub-title text-uppercase">
                Bancc
              </p>
              <h4 class="abouttrio-title about-trio-container__title">
                The users sends the bought bancc to choosed user.
              </h4>
              <!-- <small class="about-trio-container__tag">Coming Soon</small> -->
            </div>
          </b-col>
          
          <b-col md="4" cols="12">
            <div class="mb-5 about-trio-container about-trio-container--small">
              <p class="about-trio-container__sub-title text-uppercase">
                Fiat/crypto
              </p>
              <h4 class="abouttrio-title about-trio-container__title">
                The users receives the bancc and can exchange to any fiat or
                crypto they like.
              </h4>
              <!-- <small class="about-trio-container__tag">Coming Soon</small> -->
            </div>
          </b-col>
        </b-row>
        <!-- <h5 class="section-1about__paragraph mt-4">
          $BANCC —> FIAT <br />
          FIAT —> $BANCC<br />
          FIAT —> $BANCC —> FIAT<br />
        </h5> -->
        

        <h5 class="section-1about__paragraph mt-4">
          We do this to help and create an organic and steady rise in price of
          $BANCC and we do so for different reasons. First of all - we need to
          make money in order to make this project possible. Secondly - one of
          the biggest fear for people to enter the crypto world is the massive
          price volatile. The last reason might be the most fun for you - give
          back to our investors
        </h5>

        <h5 class="section-1about__paragraph mt-4">
          We will take crypto to the masses. The reasons mentioned above
          combined with a system and app so easy to use your grandmother could
          use it is a recipe for success. You can argue that this idea is
          something that a lot of projects already have tried but not in this
          way, nobody’s even close - read our WP and we can bet that you're
          joining the $BANCC community on our journey
        </h5>
       <b-dropdown id="dropdown-offset" offset="25"  text="APPLY FOR WHITELIST" variant="success" align="center" class="m-4">
              <b-dropdown-item href="https://www.bancc.io/refer" target="_blank">Apply for Whitelist</b-dropdown-item>
              <b-dropdown-item href="https://doc.bancc.io/documentation/v/launch/competitions/refer-a-friend" target="_blank">Information</b-dropdown-item>
              <b-dropdown-item href="https://doc.bancc.io/documentation/v/launch/competitions/rules" target="_blank">Rules</b-dropdown-item>
              <b-dropdown-item href="https://doc.bancc.io/documentation/v/launch/competitions" target="_blank">Competitions</b-dropdown-item>
        </b-dropdown>

        &nbsp;&nbsp;
        <a href="https://doc.bancc.io" target="_blank" rel="noopener noreferrer">
        <Button class="my-0 my-md-4" value="WHITEPAPER" /> 
        </a>
        &nbsp;&nbsp;
        <a href="https://t.me/banccio" target="_blank" rel="noopener noreferrer">
        <Button
          class="my-0 my-md-4"
          :isLink="true"
          value="JOIN TELEGRAM"
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

import icon1 from "../../assets/imgs/icon1.png";
import icon2 from "../../assets/imgs/icon2.png";
import icon3 from "../../assets/imgs/icon3.png";
import icon4 from "../../assets/imgs/icon4.png";
export default {
  components: { IconContainer, Button },
  name: "section-1About",
  data() {
    return {
      icons: [icon1, icon2, icon3, icon4],
    };
  },
};
</script>

<style lang="scss">
.section-1about {
  max-width: 60%;
  margin-left: 5%;
  letter-spacing: 1px;
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

.about-trio-container {
  width: 100%;
  height: 550px;
  border-radius: 20px;
  background: #171717;
  padding: 20px 20px 60px;
  color: #fff;
  position: relative;
  &--small {
    height: 200px;
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
  @media only screen and (max-width: 500px) {
    img {
       display: none;
    }
}
}
</style>

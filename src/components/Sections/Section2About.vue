<template>
  <div class="section-2about">
    <b-container>
      <h5 class="text-uppercase section-1__sub-title">
        Forget your bank, go BANCC.
      </h5>
      <h1 class="section-1__title title">TEAM</h1>
      <div class="section-1__move-left">
        <b-row>
          <b-col md="6" cols="12">
            <div class="mb-5 team-container team-container--small">
              <p class="team-container__sub-title text-uppercase">
                Nils-Julius Byrkjeland - Founder & CTO
              </p>
              <img src="https://firebasestorage.googleapis.com/v0/b/acies-cfc88.appspot.com/o/jul2.png?alt=media&token=d10d38e1-22b5-402f-9d3f-736fd77a601c" width="150" />
              <h4 class="mt-3 abouttrio-title team-container__title">
                Been into the crypto space since the age of 13 and created at 14
                years old his first business with Benjamin, building websites
                and apps. Currently studying Psychology apart from working on
                Bancc. He has the most technical and critical knowledge for
                blockchain development, economics and infrastructure for
                building advanced technology. He is an important part for building
                 Bancc's success.
              </h4>
            </div>
          </b-col>

          <b-col md="6" cols="12">
            <div class="mb-5 team-container team-container--small">
              <p class="team-container__sub-title text-uppercase">
                Kåre Benjamin Byrkjeland - Chief Executive Officer
              </p>
              <img src="https://firebasestorage.googleapis.com/v0/b/acies-cfc88.appspot.com/o/ben2.png?alt=media&token=a1f3c12c-786d-4090-9b42-f76a455ee720" width="150" />
              <h4 class="mt-3 abouttrio-title team-container__title">
                Benjamin is currently a professional athlete and investor in
                property, stocks and crypto. Benjamin is a junior partner in an
                online crypto casino. Benjamin started his first company when he
                was 15 years old together with Nils-Julius and has a good eye
                for seeing opportunities where others can’t see them.
              </h4>
            </div>
          </b-col>
          <b-col md="6" cols="12">
            <div class="mb-5 team-container team-container--small">
              <p class="team-container__sub-title text-uppercase">
                Isak Håkon Caldwell - Chief Financial Officer
              </p>
              <img src="https://bancc.io/files/Isak.png" width="250" />
              <h4 class="mt-3 abouttrio-title team-container__title">
                Isak has been a successful property investor since the age 
                of 18 and is now the CEO of a successful carpentry company. 
                Isak has a good ability to criticize things and see things from
                 a different perspective. With great economics experience and 
                 critical thinking Isak knows what it takes to run a successful 
                 business.
              </h4>
            </div>
          </b-col>
          <b-col md="6" cols="12">
            <div class="mb-5 team-container team-container--small">
              <p class="team-container__sub-title text-uppercase">
                Oskar Wennerlund - Lead Designer & Developer
              </p>
              <img src="https://bancc.io/files/Oskar1.png" width="120" />
              <h4 class="mt-3 abouttrio-title team-container__title">
                Oskar is a soon to be finished full stack developer.
                Oskar has an excellent eye for creating and designing 
                websites, apps and everything that comes with the process
                of doing so. Oskar will be an excellent support for 
                creating and leading the design process of the Bancc platform.
              </h4>
            </div>
          </b-col>
      
      <h1 class="section-1__title title">Advisors</h1>
      <div class="section-1__move-left">
        <b-row>
          <b-col md="4" cols="12">
            <div class="mb-5 team-container team-container--small">
              <p class="team-container__sub-title text-uppercase">
                Talal - Technical Advisor
              </p>
              <img src="" width="150" />
              <h4 class="mt-3 abouttrio-title team-container__title">
                Talal have a long experience with Network maintenance and 
                setup in the telecom industry. Talal has been with us literally
                 since day one and he has been eager and very enthusiastic 
                 about the project. We see great potential with his 
                 knowledge and skills for the more hardware/software 
                 part of the blockchain.
              </h4>
            </div>
          </b-col>
        </b-row>
      </div>
       </b-row>
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
  name: "section-2About",
  data() {
    return {
      icons: [icon1, icon2, icon3, icon4],
    };
  },
};
</script>

<style lang="scss">
.section-2about {
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
}

.team-container {
  width: 100%;
  height: 450px;
  border-radius: 20px;
  background: #171717;
  padding: 20px 20px 60px;
  color: #fff;
  position: relative;
  &--small {
    height: 450px;
    @media (max-width: 1199.98px) {
      height: auto;
    }
  }
  &__sub-title {
    color: #717271;
    letter-spacing: 1px;
    font-size: 13px;
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

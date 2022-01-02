<template>
  <div class="section-5">
    <b-container>
      <b-row class="justify-content-center">
        <b-col md="8">
          <p class="text-uppercase section-5__sub-title">Identities on the chain</p>
          <h1 class="section-5__title title">Foundation</h1>
          <h5 class="section-5__paragraph w-100 mw-100 mt-4">
            Bancc Foundation will receive 9% of the block rewards and 
            5% of the transaction fee. The foundation will be a non-profit
             organization that aims to help and build a sustainable future in 
             low income countries that are in need not only in financial 
             infrastructure but also in human necessities such as 
             food, schools, buildings, electricity etc.
          </h5>
          <b-row>
            <b-col xl="6" class="mt-5">
              <div class="section-5__card">
                <div class="section-5__card__icon-wrapper">
                  <img src="" class="section-5__card__icon" />
                </div>
                <h1 class="m-0 section-5__card__title">Users(Stakers)</h1>
                <p class="section-5__paragraph mt-2">
                  Users will receive 55% of the block reward and 10% of the 
                  transaction fee. With these rewards people will be able to
                   delegate their coins to “send free transactions” but also
                    receive a % return of the delegated coins that could 
                    be used anyway they like. Core idea behind the users 
                    receiving this reward is to incentivize users to delegate 
                    coins and keep the inflation down but also make their voice 
                    heard by giving the right to vote on new proposals created 
                    by Bancc or the community.
                </p>
              </div>
            </b-col>
            <b-col xl="6" class="d-flex mt-5">
              <div class="section-5__card">
                <div class="section-5__card__icon-wrapper">
                  <img src="" class="section-5__card__icon" />
                </div>
                <h1 class="m-0 section-5__card__title">Merchants</h1>
                <p class="section-5__paragraph mt-2">
                  Merchants will receive 9% of the block reward and 0% of the 
                  transaction fee. Anyone is eligible to join as a merchant 
                  but will need to do a KYB verification process in order 
                  to join. The merchants will be setting up light clients all 
                  around the world to help secure the blockchain and be able 
                  to process transactions in a physical or online stores.
                </p>
              </div>
            </b-col>
            <b-col xl="6" class="d-flex mt-5">
              <div class="section-5__card">
                <div class="section-5__card__icon-wrapper">
                  <img src="" class="section-5__card__icon" />
                </div>
                <h1 class="m-0 section-5__card__title">Validators</h1>
                <p class="section-5__paragraph mt-2">
                  Validators will receive 6.99% of the block reward and 80% 
                  of the transaction fee. Anyone is eligible to create a 
                  server and set up a validator. There will be a maximum 
                  of 300 validators available in the network at the same 
                  time. The validators in the network are seen as the 
                  “payment processors” whereas people that are interested 
                  in becoming a validator should treat it as running 
                  their own businesses.
                </p>
              </div>
            </b-col>
            <b-col xl="6" class="d-flex mt-5 mb-5">
              <div class="section-5__card section-5__card--gradient-bg">
                <h5 class="m-0 section-5__card__sub-title text-uppercase">
                  Newsletter
                </h5>
                <div class="d-flex align-items-center justify-content-center">
                  <img
                    src="@/assets/imgs/icon1.png"
                    class="section-5__card__icon--main"
                  />
                </div>
                <h1 class="m-0 section-5__card__title">
                  Signup to the newsletter!
                </h1>
                <div class="section-5__card__button">
                  <a href="https://serv.bancc.io/signup" target="_blank" rel="noopener noreferrer">
                  <Button :isLink="true" :noPadding="true" value="Signup" />
                  </a>
                </div>
              </div>
            </b-col>
            
            <b-col xl="6" class="d-flex section-5__card-wrapper">
              <div class="section-5__card section-5__card--gradient-bg">
                <h5 class="m-0 section-5__card__sub-title text-uppercase">
                  Validator
                </h5>
                <div class="d-flex align-items-center justify-content-center">
                  <img
                    src="@/assets/imgs/icon5.png"
                    class="section-5__card__icon--main"
                  />
                </div>
                <h1 class="m-0 section-5__card__title">
                  Apply to be one of the first validators on the Bancc Blockchain in history!
                </h1>
                <div class="">
                  <a href="https://forms.gle/P1QaUmp8Lf71XwsC6" target="_blank" rel="noopener noreferrer">
                  <Button :isLink="true" :noPadding="true" value="Apply"  />
                  </a>
                </div>
              </div>
            </b-col>
            <!-- added -->
            <b-col xl="6" class="d-flex mt-5 mb-5">
              <div class="section-5__card">
                <div class="section-5__card__icon-wrapper">
                  <img src="" class="section-5__card__icon" />
                </div>
                <h1 class=" section-5__card__title">Community</h1>
                <p class="section-5__paragraph ">
                  What is a cryptocurrency project without a community?
                  Yup, that's right. Nothing, Nada, ZER0! Therefore our two main
                  mascots for this project invites you to our BIG competition!
                  Viking Thor & Freya welcomes you! 
                  
                  
                </p>
              </div>
            </b-col>
            
            <b-col xl="6" class="d-flex  ">
              <div class="section-5__card section-5__card--gradient-bg">
                <h5 class="m-0 section-5__card__sub-title text-uppercase">
                  Community
                </h5>
                <div class="d-flex align-items-center justify-content-center">
                  <img
                    src="@/assets/imgs/Thorfreya2(1).png"
                    class="section-5__card__icon--main"
                    
                    
                  />
                </div>
                <h1 class="m-0 section-5__card__title">
                  Viking Thor & Viking Freya are waiting for you!
                  
                  200K$ in PRIZES!
                </h1>
                <div class="section-5__card__button">
                  <a href="https://t.me/VikingThorBot" target="_blank" rel="noopener noreferrer">
                  <Button :isLink="true" :noPadding="true" value="Join now!"  />
                  </a>
                </div>
              </div>
            </b-col>
            
            <!-- added end -->
          </b-row>
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
  name: "section-5",
};
</script>

<style lang="scss">
.section-5 {
  margin-top: 200px;

  &__title {
    color: #fff;
    text-transform: uppercase;
  }
  &__sub-title {
    color: #717271;
    letter-spacing: 1px;
    font-weight: 600;
    transform: rotate(90deg);
    display: inline-block;
    margin-left: -80px;
    margin-bottom: 150px;
  }
  &__paragraph {
    color: #fff;
    font-weight: 300;
    font-size: 16px;
    @media (max-width: 991.98px) {
      max-width: 80%;
    }
  }
  &__card {
    &-wrapper {
      margin-top: -250px;
      @media (max-width: 1199.98px) {
        margin-top: auto;
      }
    }
    &__sub-title {
      color: #717271;
      letter-spacing: 1px;
      font-weight: 600;
      font-size: 14px;
    }
    &__title {
      color: #fff;
      font-weight: 700;
      font-size: 30px;
    }
    &__info {
      color: #fff;
      font-size: 12px;
      margin-top: -8px;
      display: block;
    }
    &--gradient-bg {
      background: linear-gradient(#000, #1d1b1e, #009245 );
      border-radius: 25px;
      padding: 20px 20px 60px;
      width: 100%;
      height: 550px;
      .section-5__card {
        &__title {
          padding: 300px 0 0;
        }
      }
      @media (max-width: 1199.98px) {
        height: auto;
      }
    }
    &__button {
      position: absolute;
      bottom: 20px;
    }
    &__icon {
      &--main {
        position: absolute;
        width: 110%;
        top: -5%;
        left: 50%;
        transform: translateX(-50%);
        @media (max-width: 1199.98px) {
          width: 70%;
        }
      }
    }
  }
}
</style>

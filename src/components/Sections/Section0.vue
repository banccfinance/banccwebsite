<template>
  <div class="section-0">
    <b-container>
      <h5 class="text-uppercase section-1__sub-title">
        Forget your bank, go BANCC.
      </h5>
      
      <h1 class="section-1__title title">BANCC<br />VISION</h1>
      <div class="section-1__move-left">
        <div class="mb-5 coming-soon-container coming-soon-container--small">
                
                <h5 class="section-1__paragraph mt-1">
                  Bancc is a Blockchain company that are setting sail on creating
                  the next decentralized financial platform by bridging 
                  the gap between existing technologies with blockchain possibilities. <br><br>
                  With our platform we are solving everyday problems all around the world such as;<br>
                  &nbsp;&nbsp;&nbsp;&nbsp;Money remittance services high fees<br>
                  &nbsp;&nbsp;&nbsp;&nbsp;Money payment processing high fees<br>
                  &nbsp;&nbsp;&nbsp;&nbsp;Selling & Reselling items on marketplaces high fees <br><br>
                </h5>

                <div class="blink_me">
            <a href="https://refer.bancc.io" target="_blank" rel="noopener noreferrer" style="text-decoration: none; color: #009245;" >
              <h4>
                <br>
                JOIN THE WHITELIST TODAY! EARN 10$ FOR EACH FRIEND YOU REFER!
              </h4>
              </a>
               
          </div>
                
                <!-- <small class="coming-soon-container__tag">Coming Soon</small> -->
              </div>
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
   
<img src="https://bancc.io/files/bancapp1.png" width="1000" align="right" />


    
    
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
  name: "section-0",
  data() {
    return {
      icons: [icon1, icon2, icon3, icon4],
    };
  },
};
</script>

<style lang="scss">
.section-0 {
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

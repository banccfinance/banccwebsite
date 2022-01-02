<template>
    <b-container>
      <div class="section-3about">
        <h1 class="section-1__title title" align="center">Community</h1>
        <h5 class="text-uppercase section-1__sub-title" align="center">
        THE COMMUNITY THAT ALWAYS SHINES.
        </h5>
      </div>
    
        <b-row>
           <b-col >
                <div class="mb-5 team-container team-container1--small">
                <p class="team-container__sub-title text-uppercase" align="center">
                    BRYAN AGAS(BRAX) <br> COMMUNITY MANAGER & INFLUENCER <br> United Kingdom
                </p>
                
                <img src="https://bancc.io/files/brax-crop.png"  class="circleteam" />
                <a href="https://www.linkedin.com/in/bryanagas/" target="_blank" rel="noopener noreferrer" align="center">
                    <Button 
                    class="my-0 my-md-1"
                    :isLink="true"
                    value="LinkedIn"
                    icon="fab fab fa-linkedin"
                    />
                    </a>
                    <a href="https://t.me/cryptobrax" target="_blank" rel="noopener noreferrer">
                    <Button
                    class="my-0 my-md-1"
                    :isLink="true"
                    value="TG"
                    icon="fab fa-telegram-plane"
                    />
                    </a>
                    <h5 class=" abouttrio-title " align="center">
                    Brax is a cryptoenthusiast and influencer from the UK. 
                    We believe that Brax has excellent communication skills 
                    that resembles "Bancc's Vision" - transparency, honesty and inclusiveness. 
              </h5>
            </div>
          </b-col>
          <b-col >
                <div class="mb-5 team-container team-container1--small">
                <p class="team-container__sub-title text-uppercase" align="center">
                    RAZA <br> CHIEF EDITOR <br> United Arab Emirates
                </p>
                
                <img src="https://bancc.io/files/raza-crop.png"  class="circleteam" />
                <a href="https://www.linkedin.com/in/agha-muhammad-raza-7677b5119" target="_blank" rel="noopener noreferrer" align="center">
                    <Button 
                    class="my-0 my-md-1"
                    :isLink="true"
                    value="LinkedIn"
                    icon="fab fab fa-linkedin"
                    />
                    </a>
                    <a href="https://t.me/amraza24" target="_blank" rel="noopener noreferrer">
                    <Button
                    class="my-0 my-md-1"
                    :isLink="true"
                    value="TG"
                    icon="fab fa-telegram-plane"
                    />
                    </a>
                    <h5 class=" abouttrio-title " align="center">
                    Raza is an excellent article writer and loves 
                    cryptocurrency so much that he started to write about it.
                    Based from Pakistan, Raza will be the first lead writer for 
                    Bancc, updating the community and social media about the 
                    upcoming excting things!
              </h5>
            </div>
          </b-col>
            <b-col >
                <div class="mb-5 team-container team-container1--small">
                <p class="team-container__sub-title text-uppercase" align="center">
                    YOU? <br> OR <br> SOMEONE YOU KNOW?
                </p>
                
                <img src="https://bancc.io/files/you.png"  class="circleteam" />
                <br><br>
                    <h5 class=" abouttrio-title " align="left">
                    Do you want to be a part of the Bancc team? We are currently in need of -
                    
                    <br>&nbsp;&nbsp; - Developers (Golang & Solidity)
                    <br>&nbsp;&nbsp; - Influencers / Promoters
                    <br>&nbsp;&nbsp; - Social Media Partners
                    <br>&nbsp;&nbsp; - Translators 
              </h5>
              <a href="mailto:contact@bancc.io" target="_blank" rel="noopener noreferrer" align="center"> Send resume to contact@bancc.io </a>
            </div>
          </b-col>
        </b-row>
    </b-container>
  
  
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
  name: "section-3About",
  data() {
    return {
      icons: [icon1, icon2, icon3, icon4],
    };
  },
};
</script>

<style lang="scss">

.profilebutton {
    display: block;
    margin-left: auto;
    margin-right: auto;
    align: center;
}
.circleteam {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;

}
.section-3about {
  letter-spacing: 1px;
  margin-left: 0%;
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

.team-container1 {
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

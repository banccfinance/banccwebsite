<template>
  <b-container>
    <div class="footer">
      <h4>Information</h4>
      <p>
        Copyright © 2021 Spaceium Ltd. All rights reserved. <a href="https://docs.google.com/document/d/1AurVe1ODumOja8ng1j0OnaadZxYopGf6Hs7SgSADNsg/edit?usp=sharing" target="_blank" rel="noopener noreferrer">
         Privacy Policy </a> <a href="https://docs.google.com/document/d/18TFPyJYHxArQq-R312DqlXSVDnWVpXQyyZvbW6NIFzY/edit?usp=sharing" target="_blank" rel="noopener noreferrer">
         Terms & Conditions </a>
        
      </p>
      <div class="d-flex justify-content-between">
        <a v-for="(item,i) in social_media" :key="i" :href="item.url" target="_blank" rel="noopener noreferrer">
        <i class="footer__icon d-flex d-md-none d-lg-none"  :class="`${item.ic} fa-1x`"></i>
        <i class="footer__icon d-none d-md-flex d-lg-flex"   :class="`${item.ic} fa-3x`"></i>

        </a>
      </div>
    </div>
  </b-container>
</template>

<script>
export default {
  name:'Footer',
  data(){
    return {
      social_media:[
        {
          ic:'fab fa-github',
          url:'https://github.com/banccio'
        },
        {
          ic:'fab fa-twitter',
          url:'https://twitter.com/Banccio'
        },
        {
          ic:'fab fa-discord',
          url:'https://discord.gg/B39UTqhRnh'
        },
        {
          ic:'fab fa-telegram',
          url:'Https://t.me/banccio'
        },
        {
          ic:'fas fa-bullhorn',
          url:'Https://t.me/banccann'
        },
        
        {
          ic:'fab fa-medium-m',
          url:'Https://blog.bancc.io'
        },
        {
          ic:'fab fa-facebook',
          url:'https://www.facebook.com/Bancc.io'
        },
        {
          ic:'fab fa-linkedin',
          url:'https://www.linkedin.com/company/spaceium-io'
        },
        {
          ic:'fab fa-instagram',
          url:'https://www.instagram.com/bancc_io/'
        }
      ]
    }
  }

};
</script>

<style lang="scss">
.footer {
  color: #fff;
  border-top: 2px solid #fff;
  padding: 20px 0;
  margin-top: 200px;
  &__icon{
    color:#009149;
    text-shadow: 0 0 50px #009149
  }
}
</style>

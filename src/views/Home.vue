<template>
  <div class="home">
    <div class="bg-1-wrapper">
      <navbar />
      <section-0 />
    </div>
     <div class="bg-2-wrapper-inv">
      <section-1 />
    </div>
    <div class="bg-2-wrapper">
      <section-2 />
    </div>
    <div class="bg-s3-wrapper">
      <section-3 />
    </div>
    <div class="bg-3-wrapper">
      <section-planet />
    </div>
    <div class="bg-4-wrapper mt-n5">
      <section-4 />
      <section-5 />
    </div>
    <Footer />
  </div>
</template>

<script>
import Footer from "../components/Footer.vue";
import Navbar from "../components/Navbar.vue";
import Section0 from "../components/Sections/Section0.vue";
import Section1 from "../components/Sections/Section1.vue";
import Section2 from "../components/Sections/Section2.vue";
import Section3 from "../components/Sections/Section3.vue";
import Section4 from "../components/Sections/Section4.vue";
import Section5 from "../components/Sections/Section5.vue";
import SectionPlanet from "../components/Sections/SectionPlanet.vue";

export default {
  name: "Home",
  components: {
    Navbar,
    Section0,
    Section1,
    Section2,
    Section3,
    Section4,
    Section5,
    SectionPlanet,
    Footer,
  },
};
</script>

<style>
.bg-1-wrapper {
  background: url("~@/assets/imgs/bg-4.png");
  background-repeat: no-repeat;
  background-size: contain;
}
.bg-2-wrapper {
  background: url("~@/assets/imgs/bg-2.png");
  background-repeat: no-repeat;
  background-size: contain;
  background-position: right center;
  padding: 200px 0;
}
.bg-2-wrapper-inv {
  background: url("~@/assets/imgs/bg-4-rev.png");
  background-repeat: no-repeat;
  background-size: contain;
  background-position:  center right;
  padding: 200px 0;
}
.bg-s3-wrapper {
  background: url("~@/assets/imgs/bg-2.png");
  background-repeat: no-repeat;
  background-size: 30%;
  background-position: center center;
  
}
.bg-3-wrapper {
  background: url("~@/assets/imgs/bg-3.png");
  background-repeat: no-repeat;
  background-size: contain;
  background-position: right center;
  
}
@media (max-width: 991.98px) {
  .bg-3-wrapper {
    padding: 550px 0;
  }
}
@media (max-width: 767.98px) {
  .bg-3-wrapper {
    padding: 350px 0;
  }
}
.bg-4-wrapper {
  background: url("~@/assets/imgs/bg-4-old.png");
  background-repeat: no-repeat;
  background-size: contain;
  background-position: left center;
}
</style>

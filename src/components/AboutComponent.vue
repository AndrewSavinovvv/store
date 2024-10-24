<script setup>

import BottomComponent from "@/components/BottomComponent.vue";
</script>

<template>
  <div class="about">
    <div class="about__left">
     <div class="about__left__details">
       <h3 class="about__left__title">The furniture brand for the future, with timeless designs</h3>
     <BottomComponent class="btn__desktop"></BottomComponent>
       <h6 class="about__left__text">
         A new era in eco friendly furniture with Avelon, the French luxury retail brand
         with nice fonts, tasteful colors and a beautiful way to display things digitally
         using modern web technologies.
       </h6>
     </div>
      <BottomComponent class="btn__mob"></BottomComponent>
    </div>
    <div class="about__right">
      <img class="about__right__img" src="@/assets/aboutimg/Right%20Image.png" alt="">
    </div>
  </div>
</template>

<style scoped>
.about {
  display: flex;
  margin-top: 60px;
}
.about__left {
  background: #2A254B;
  color: white;
  padding: 60px;
}
.about__left__title {
  font-size: 32px;
  font-weight: 400;
  line-height: 44px;
}
.about__left__text{
  font-size: 18px;
  font-weight: 400;
  line-height: 27px;
}

.about__left__details {
  display: flex;
  flex-wrap: wrap;
}
.about__right__img {
  display: flex;
}

.btn__mob {
  display: none;
}
@media (max-width: 887px) {
  .about__left {
    padding: 0;
  }
  .about__right {
    display: none;
  }
  .about__left__details {
    padding: 24px;
  }
  .about__left {
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  .btn__mob {
    display: block;
    margin: 24px;
    font-weight: 100;
  }
  .btn__desktop {
    display: none;
  }
  .about__left__title{
    margin-bottom: 90px;
    font-size: 30px;
    font-weight: 100;
  }
  .about__left__text {
    margin: 0;
    font-weight: 100;
  }
}
</style>
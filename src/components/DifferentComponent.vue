<script setup>

</script>

<template>
  <div class="different">
    <h2 class="different__title">What makes our brand different</h2>
    <div class="different__block">
      <ul class="different__block__list">
        <li class="different__block__list__item">
          <img src="@/assets/differentimg/Delivery.png" alt="">
          <span class="different__block__list__item__title">Next day as standard</span>
          <span class="different__block__list__item__text">Order before 3pm and get your order
the next day as standard</span>
        </li>
        <li class="different__block__list__item">
          <img src="@/assets/differentimg/Checkmark--outline.png" alt="">
          <span class="different__block__list__item__title">Made by true artisans</span>
          <span class="different__block__list__item__text">Handmade crafted goods made with
real passion and craftmanship</span>
        </li>
        <li class="different__block__list__item">
          <img src="@/assets/differentimg/Purchase.png" alt="">
          <span class="different__block__list__item__title">Unbeatable prices</span>
          <span class="different__block__list__item__text">For our materials and quality you won’t find better prices anywhere</span>
        </li>
        <li class="different__block__list__item">
          <img src="@/assets/differentimg/Sprout.png" alt="">
          <span class="different__block__list__item__title">Recycled packaging</span>
          <span class="different__block__list__item__text">We use 100% recycled packaging to ensure our footprint is manageable</span>
        </li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
.different {
  margin-top: 60px;
}
.different__block {
  display: flex;
}
.different__block__list{
  display: flex;
  list-style: none;
  padding: 0;
}
.different__block__list__item {
  display: flex;
  flex-direction: column;

}
.different__block__list__item img {
  height: 24px;
  width: 24px;
}
.different__block__list__item__title {
  color: #2A254B;
  font-size: 20px;
  font-weight: 400;
  line-height: 28px;
  padding-top: 16px;
}
.different__block__list__item__text {
  font-size: 16px;
  font-weight: 400;
  line-height: 24px;
  color: #2A254B;
  padding-top: 8px;
}
.different__title {
  display: flex;
  justify-content: center;
  color: #2A254B;
  font-size: 24px;
  font-weight: 400;
  line-height: 33px;
}
@media (max-width: 887px) {
  .different {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 24px;
    margin: 0;
  }
  .different__title {
    justify-content: flex-start;
    font-size: 20px;

  }
  .different__block {
    flex-direction: column;
  }
  .different__block__list {
    flex-direction: column;
  }
  .different__block__list__item {
    margin-bottom: 36px;
  }
}

</style>
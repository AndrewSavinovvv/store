<script setup>

</script>

<template>
  <div class="popular">
    <h2 class="popular__section__title">Our popular products</h2>
    <div class="popular__section__list">
      <div class="popular_card" >
        <img src="@/assets/popularimg/Large.png"  class="popular__card__image">
        <h3 class="popular__card__title">The Poplar suede sofa</h3>
        <span class="popular__card__price">£980</span>
      </div>
      <div class="popular__card" >
        <img src="@/assets/ceramicsimg/chair.png"  class="popular__card__image">
        <img src="@/assets/ceramicsimg/lamp.png"  class="popular__card__image2">
        <h3 class="popular__card__title">The Dandy chair</h3>
        <h3 class="popular__card__title2">The Lucy Lamp</h3>
        <span class="popular__card__price">£250</span>
        <span class="popular__card__price2">£399</span>
      </div>
      <div class="popular__card" >
        <img src="@/assets/popularimg/Photo.png"  class="popular__card__image">
        <img src="@/assets/ceramicsimg/Parent.png"  class="popular__card__image2">
        <h3 class="popular__card__title">The Dandy chair</h3>
        <h3 class="popular__card__title2">Rustic Vase Set</h3>
        <span class="popular__card__price">£250</span>
        <span class="popular__card__price2">£155</span>
      </div>
    </div>
    <div class="popular__btn__block">
      <button class="popular__btn">View collection</button>
    </div>
  </div>
</template>

<style scoped>
.popular {
  display: flex;
  flex-direction: column;
  margin-top: 80px;
}

.popular__section__title {
  display: flex;
}

.popular__section__list {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.popular__card {
  flex: 1 1 25%;
  box-sizing: border-box;
  padding: 10px;
}

.popular__section__title {
  font-size: 32px;
  font-weight: 400;
  line-height: 39px;
  color: #2A254B;
}

.popular__card__image {
  max-width: 100%;
  height: auto;
}

.popular__card__title {
  font-size: 20px;
  line-height: 28px;
  font-weight: 400;
}

.popular__card__price {
  color: #2A254B;
  font-size: 18px;
  font-weight: 400;
  line-height: 27px;
}
.popular__btn {
  background:#F9F9F9;
  border: none;
  color: #2A254B;
  padding: 16px 32px;
  font-size: 16px;
  font-weight: 400;
  line-height: 24px;
  margin-bottom: 60px;
  font-family: "Lexend Exa", sans-serif;
  cursor: pointer;
}
.popular__btn__block {
  display: flex;
  justify-content: center;
  padding-top: 35px;
}
.popular__card__image2 {
  display: none;
}
.popular__card__title2{
  display: none;
}
.popular__card__price2{
  display: none;
}
@media (max-width: 887px) {
  .popular{
    padding: 24px;
  }
  .popular__section__title {
    font-size: 20px;
    font-weight: 400;
    color: #2A254B;

  }
  .popular__section__list {
    display: flex;
    gap: 16px;
  }
  .popular__card {
    flex: none;
    padding: 0;
  }
  .popular__btn {
    width: 100%;
    cursor: pointer;
  }
  .popular_card:nth-child(1) {
    display: none;
  }
  .popular__card__image2 {
    display: flex;
    width: 195px;
    height: 251px;
    overflow: hidden;

  }
  .popular__card__image {
    display: none;
  }
  .popular__card__price,.popular__card__title {
    display: none;
  }
  .popular__card__price2,.popular__card__title2 {
    display: flex;
    font-weight: 400;
  }
}

</style>
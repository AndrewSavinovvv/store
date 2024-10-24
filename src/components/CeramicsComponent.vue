<script setup>

</script>

<template>
  <div class="product__section">
    <h2 class="product__section__title">New ceramics</h2>
    <div class="product__section__list">
      <div class="product__card" >
        <img src="@/assets/ceramicsimg/chair.png"  class="product__card__image">
        <h3 class="product__card__title">The Dandy chair</h3>
        <span class="product__card__price">£250</span>
      </div>
      <div class="product__card" >
        <img src="@/assets/ceramicsimg/Parent.png"  class="product__card__image">
        <h3 class="product__card__title">Rustic Vase Set</h3>
        <span class="product__card__price">£155</span>
      </div>
      <div class="product__card" >
        <img src="@/assets/ceramicsimg/Parent%20(1).png"  class="product__card__image">
        <h3 class="product__card__title">The Silky Vase</h3>
        <span class="product__card__price">£125</span>
      </div>
      <div class="product__card" >
        <img src="@/assets/ceramicsimg/lamp.png"  class="product__card__image">
        <h3 class="product__card__title">The Lucy Lamp</h3>
        <span class="product__card__price">£399</span>
      </div>
    </div>
    <div class="product__btn__block">
      <button class="product__btn">View collection</button>
    </div>
  </div>
</template>


<style scoped>
.product__section {
  display: flex;
  flex-direction: column;
  margin-top: 80px;
}

.product__section__title {
  display: flex;
}

.product__section__list {
  display: flex;
  justify-content: space-between;
}

.product__card {
  flex: 1 1 25%;
  box-sizing: border-box;
  padding: 10px;
}

.product__section__title {
  font-size: 32px;
  font-weight: 400;
  line-height: 39px;
  color: #2A254B;
}

.product__card__image {
  max-width: 100%;
  height: auto;
}

.product__card__title {
  font-size: 20px;
  line-height: 28px;
  font-weight: 400;
}

.product__card__price {
  color: #2A254B;
  font-size: 18px;
  font-weight: 400;
  line-height: 27px;
}
.product__btn {
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
.product__btn__block {
  display: flex;
  justify-content: center;
  padding-top: 35px;
}
@media (max-width: 887px) {
  .product__section{
    padding: 24px;
  }
  .product__section__title {
    font-size: 20px;
    font-weight: 400;
    color: #2A254B;

  }
  .product__section__list {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 16px;
  }
  .product__card {
    flex: none;
    padding: 0;
  }
  .product__btn {
    width: 100%;
    cursor: pointer;
  }
}

</style>
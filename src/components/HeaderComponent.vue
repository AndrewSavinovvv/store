<script setup>

</script>

<script setup>
</script>

<template>
  <div class="header">
    <div class="header__search">
      <img src="@/assets/headerimg/search.png" alt="">
      <div class="burger__menu">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>
    <div>
      <h3 class="header__title">Avion</h3>
    </div>
    <div class="header__btns">
      <img src="@/assets/headerimg/cart.png" alt="">
      <img src="@/assets/headerimg/user.png" alt="">
    </div>
  </div>
  <div class="header__line"></div>
  <div class="header__nav">
    <ul class="header__nav__list">
      <li>Plant pots</li>
      <li>Ceramics</li>
      <li>Tables</li>
      <li>Chairs</li>
      <li>Crockery</li>
      <li>Tableware</li>
      <li>Cutlery</li>
    </ul>
  </div>
</template>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 26px;
}
.header__title {
  color: #22202E;
  font-weight: 400;
  font-size: 24px;
}
.header__btns img {
  margin-left: 16px;
}
.header__line {
  border: 1px solid #22202E;
  margin: 20px 28px;
}
.header__nav {
  display: flex;
  justify-content: center;
  color: #726E8D;
}
.header__nav__list {
  display: flex;
  list-style: none;
  font-weight: 400;
  font-size: 16px;
}
.header__nav__list li {
  margin-right: 44px;
}

.burger__menu {
  display: none;
  flex-direction: column;
  justify-content: space-between;
  width: 24px;
  height: 20px;
  cursor: pointer;
}

.burger__menu span {
  display: block;
  width: 100%;
  height: 2px;
  background-color: #22202E;
}

@media (max-width: 887px) {
  .header__nav,
  .header__line,
  .header__btns {
    display: none;
  }
  .header {
    display: flex;
    flex-direction: row-reverse;
    padding: 26px 20px;
  }
  .header__search {
    display: flex;
    align-items: center;
  }
  .burger__menu {
    display: flex;
  }
  .header__search img {
    margin-right: 20px;
  }
}
</style>
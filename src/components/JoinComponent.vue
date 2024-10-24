<script setup>

</script>

<template>
  <div class="join">
    <div class="join__content">
      <h2 class="join__content__title">Join the club and get the benefits</h2>
      <h6 class="join__content__text">Sign up for our newsletter and receive exclusive offers on new <br> ranges, sales, pop up stores and more</h6>
      <div class="join__content_input">
        <input class="join__input" type="email" placeholder="your@email.com">
        <button class="join__btn">Sign up</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.join {
  background-color: #F9F9F9;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 50vh;
}

.join__content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  background-color: #FFFFFF;
  padding: 92px 0;
  margin-top: 52px;
  width: 1280px;
}

.join__content_input {
  display: flex;
  align-items: center;
  width: 100%;
  justify-content: center;
}

.join__content__title {
  color: #2A254B;
  font-size: 36px;
  font-weight: 400;
}

.join__content__text {
  font-size: 16px;
  text-align: center;
  font-weight: 400;
}

.join__input {
  width: 354px;
  padding: 20px;
  color: #2A254B;
  border: none;
  border-radius: 0;
  background: #F9F9F9;
}

input::placeholder {
  color: lightgrey;
  padding: 17px 32px;
}

.join__btn {
  background-color: #2A254B;
  color: white;
  font-size: 16px;
  font-weight: 400;
  padding: 16px 32px;
  border-radius: 0;
  cursor: pointer;
  font-family: "Lexend Exa", sans-serif;
}
@media (max-width: 887px) {
  .join {
    padding: 24px;
    background: white;
  }

  .join__content {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0;
  }

  .join__content__title {
    font-size: 20px;
    font-weight: 300;
    text-align: left;
  }

  .join__content__text {
    font-size: 14px;
    font-weight: 300;
    text-align: left;
    margin-bottom: 64px;
  }
  .join__input {
    width: 100%;
    margin-right: 0;
    margin-bottom: 16px;
    align-items: center;
  }
  .join__btn {
    height: 56px;
    align-items: center;
    padding: 10px 32px;
    white-space: nowrap;
  }
  .join__content_input {
    display: flex;
    align-items: flex-start;
  }
}
</style>
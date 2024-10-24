<script setup>

</script>

<template>
  <div class="history">
    <div class="history__left">
      <div>
        <h2 class="history__left__title">From a studio in London to a global brand with
          over 400 outlets</h2>
        <h6 class="history__left__text">When we started Avion, the idea was simple. Make high quality furniture affordable and available for the mass market.</h6>
        <p class="history__left__text2">Handmade, and lovingly crafted furniture and homeware is what we live, breathe and design so our Chelsea boutique become the hotbed for the London interior design community.</p>
      </div>
      <div>
        <button class="history__btn">Get in touch</button>
      </div>
    </div>
    <div class="history__right">
      <div>
        <img class="history__right__img" src="@/assets/historyimg/image.png" alt="">
      </div>
    </div>
  </div>
</template>

<style scoped>
.history {
  display: flex;
  margin-top: 65px;
  color: #2A254B;
  gap: 122px;
}
.history__left {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.history__left__title {
  font-size: 24px;
  font-weight: 400;
  margin-top: 0;
}
.history__left__text, .history__left__text2 {
  font-size: 16px;
  font-weight: 400;
  color: #505977
}
.history__btn {
  background: #F9F9F9;
  color: #2A254B;
  border: none;
  padding: 16px 32px;
  font-family: "Lexend Exa", sans-serif;
  margin-bottom: 54px;
}
.history__right{
  width: 100%;
  max-width: 720px;
  height: auto;
}
.history__right__img {
  width: 100%;
  height: auto;
}
@media (max-width: 887px) {
  .history {
    display: flex;
    flex-direction: column;
    padding: 0 24px;
    margin: 0;
    gap: 0;
  }
  .history__left__text2 {
    padding-bottom: 64px;
    font-size: 14px;
  }
  .history__btn {
    width: 100%;
    margin: 0;
  }
  .history__left__text {
    font-size: 14px;
  }
  .history__left__title {
    font-size: 20px;
    padding-right: 80px;
  }
  .history__right{
    margin-top: 50px;
  }
  .history__right__img {
    width: 100%;
  }
}
</style>
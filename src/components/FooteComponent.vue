<script setup>

</script>

<template>
 <div class="footer">
   <div class="footer__menu"> <h6>Menu</h6>
     <ul>
       <li class="footer__item">New arrivals</li>
       <li class="footer__item">Best sellers</li>
       <li class="footer__item">Recently viewed</li>
       <li class="footer__item">Popular this week</li>
       <li class="footer__item">All products</li>
     </ul>
   </div>
   <div class="footer__categories"> <h6>Categories</h6>
     <ul>
       <li class="footer__item">Crockery</li>
       <li class="footer__item">Furniture</li>
       <li class="footer__item">Homeware</li>
       <li class="footer__item">Plant pots</li>
       <li class="footer__item">Chairs</li>
       <li class="footer__item">Crockery</li>
     </ul>
   </div>
   <div class="footer__info"> <h6>Our company</h6>
     <ul>
       <li class="footer__item">About us</li>
       <li class="footer__item">Vacancies</li>
       <li class="footer__item">Contact us</li>
       <li class="footer__item">Privacy</li>
       <li class="footer__item">Returns policy</li>
     </ul>
   </div>
   <div>
     <h6 class="footer__title">Join our mailing list</h6>
     <div class="footer__sign">
       <input class="footer__sign__input" type="text" placeholder="your@email.com">
       <button class="footer__sign__btn">Sing Up</button>
     </div>
   </div>
 </div>
  <div class="footer__line"></div>
 <div class="footer__title2">
   <h6 class="footer__title2__h6" >Copyright 2022 Avion LTD</h6>
 </div>
  <div class="footer__social">
    <div class="footer__title__main">
      <h6 class="footer__title">Copyright 2022 Avion LTD</h6>
    </div>
    <div class="social">
      <ul class="social__list">
        <li class="social__item">
          <img src="@/assets/socialimg/Logo--linkedin.png" alt="">
        </li>
        <li class="social__item">
          <img src="@/assets/socialimg/Logo--facebook.png" alt="">
        </li>
        <li class="social__item">
          <img src="@/assets/socialimg/Logo--instagram.png" alt="">
        </li>
        <li class="social__item">
          <img src="@/assets/socialimg/Logo--skype.png" alt="">
        </li>
        <li class="social__item">
          <img src="@/assets/socialimg/Logo--twitter.png" alt="">
        </li>
        <li class="social__item">
          <img src="@/assets/socialimg/Logo--pinterest.png" alt="">
        </li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
.footer {
  background: #2A254B;
  color: white;
  display: flex;
  justify-content: space-between;
  padding: 58px 82px;
}
.footer__menu ul,.footer__categories ul, .footer__info ul {
  display: flex;
  flex-direction: column;
  list-style: none;
  margin: 0;
  padding: 0;
  font-size: 16px;
}
.footer__menu ,.footer__categories , .footer__info  {
  display: flex;
  flex-direction: column;
  justify-content: start;
}
.footer__menu h6 ,.footer__categories h6, .footer__info h6 {
  font-size: 16px;
  margin: 0;
}
.footer__item{
  font-size: 14px;
  margin-top: 16px;
  font-weight: 300;
}
.footer__title {
  font-size: 16px;
  margin: 0;
  font-weight: 300;
}
.footer__sign{
  padding-top: 16px;
  width: 100%;
}
input::placeholder {
  background: none;
  color: white;
}

.footer__sign__input {
  padding: 17px 32px;
  color: #2A254B;
  border: none;
  border-radius: 0;
  background: #FFFFFF26;
}
.footer__sign__btn{
  padding: 16px 32px;
  font-family: "Lexend Exa", sans-serif;
}
.footer__line {
  border: 1px solid #4E4D93;
}
.footer__social {
  background: #2A254B;
}
.social__list {
  display: flex;
  list-style: none;
}
.social {
  display: flex;
  justify-content: space-between;
}
.footer__social {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 82px;
}

.social {
  display: flex;
}

.social__list {
  display: flex;
  list-style: none;
  gap: 16px;
  margin: 0;
  padding: 0;
  cursor: pointer;
}
.footer__title {
  font-size: 14px;
  color: white;
}
.footer__title2 {
display: none;
}
@media (max-width: 887px) {
  .footer {
    flex-wrap: wrap;
    padding: 25px 40px;

  }

  .footer__menu,
  .footer__categories,
  .footer__info {
    flex: 1 0 50%;
    box-sizing: border-box;
    padding: 10px 10px;
  }

  .footer__sign {
    display: flex;
    width: 100%;
    margin-top: 20px;
  }

  .footer__title {
    flex-basis: 100%;
    margin-top: 40px;
  }
  .footer__sign__input {
    padding: 20px;
  }
  .footer__social {
    flex-basis: 100%;
    justify-content: center;
  }
  .social__item {
    display: none;
  }
  .footer__title2 {
    display: flex;
    background: #2A254B;
    color: white;
    justify-content: center;
  }
  .footer__title2__h6 {
    font-size: 14px;
    font-weight: 400;
  }
}
</style>
<template>
  <div class="concept">
    <div class="d-flex flex-wrap justify-content-center col-xl-6">
      <p class="concept_price_title col-xl-12 mb-5 pb-5">PRICE</p>
      <p class="concept_price col-xl-12 pb-5 mb-5 mt-5">55</p>
      <p class="concept_eur_mo col-xl-12 pb-4">EUR/MO</p>
      <button class="concept_button"><span>SIGN UP</span></button>
    </div>
  </div>
</template>
<style scoped>
.concept {
  position: relative;
  height: 100vh;
  width: 100%;
  position: relative;
  background-image: url("../../assets/images/landingPageImg/1003@3x.png");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center center;
  background-color: red;
  padding-bottom: 50px;
}
.concept > div {
  position: absolute;
  left: 24%;
  top: 42%;
}

.concept_price_title {
  font-family: Montserrat;
  font-size: 70px;
  font-weight: 600;
  line-height: 0.34;
  text-align: center;
  color: #000000;
}
.concept_price {
  font-family: Montserrat;
  font-size: 130px;
  font-weight: 600;
  line-height: 0.18;
  text-align: center;
  color: #edcb50;
}
.concept_eur_mo {
  font-family: Montserrat;
  font-size: 50px;
  font-weight: 600;
  line-height: 0.48;
  text-align: center;
  color: #000000;
}
.concept_button {
  width: 251.4px;
  height: 79.5px;
  border-radius: 25px;
  border: solid 1px #111111;
  background-image: linear-gradient(324deg, #242424 73%, #3b3b3b 27%);
}
.concept_button span {
  font-family: Montserrat;
  font-size: 31.8px;
  font-weight: 900;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.2;
  letter-spacing: normal;
  text-align: center;
  color: #edcb50;
}
</style>

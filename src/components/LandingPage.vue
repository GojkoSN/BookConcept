<template>
  <div class="landing_page row">
    <nav-bar></nav-bar>

    <div class="col-xl-12 second_part">
      <div class="col-xl-4 d-flex flex-wrap landingPage_headline_wrapper">
        <p class="landingPage_headline">
          Mauris enim tellus, finibus in enim tellus
        </p>
        <p class="landingPage_subtitle">
          Aenean ultricies iaculis cursus. Mauris enim tellus, finibus in felis
          sollicitu din iaculis dolor. Donec sollicitudin orci id efficitur
          dapibus. Aliq uamtem por ien sed condimentum fringilla. In magna elit,
          ultrices a eros it amet, iaculis hendrerit tellusn iaculis nisi, nec
          maximus lorem.
        </p>
        <button class="col-xl-5 mr-5 free_demo">FREE DEMO</button>
        <button class="col-xl-5 sign_up">SIGN UP</button>
      </div>
    </div>
  </div>
</template>
<script>
import navBar from "../components/shared/Navigation.vue";
export default {
  components: {
    "nav-bar": navBar
  }
};
</script>
<style scoped>
.landing_page {
  object-fit: contain;
  margin: 0;
  padding: 0;
}
.landing_page:first-child {
  background-color: #d9b22b;
}
.second_part {
  position: relative;
  background-image: url("../assets/images/landingPageImg/web.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center center;
  background-color: red;
}
.landingPage_headline_wrapper {
  margin-left: 250px;
  padding-bottom: 260px;
}
.landingPage_headline {
  margin-top: 320px;
  font-family: DancingScript;
  font-size: 80px;
  font-weight: bold;
  line-height: 1;
  text-align: left;
  color: #302e2f;
}
.landingPage_subtitle {
  font-family: Montserrat;
  font-size: 20px;
  line-height: 1.2;
  text-align: left;
  color: #302e2f;
}
button {
  height: 50px;
  border-radius: 25px;
  border: solid 1px #111111;
}
.free_demo {
  background-color: transparent;
}
.sign_up {
  background-color: black;
  font-size: 20px;
  font-weight: 900;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.2;
  letter-spacing: normal;
  text-align: center;
  color: #edcb50;
}
.landingPage_book {
  position: absolute;
  left: 50%;
  top: 50%;
}
</style>

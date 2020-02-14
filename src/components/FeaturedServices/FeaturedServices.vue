<template>
  <div class="col-xl-9 text-center">
    <h2 class="title">
      <span>
        <div class="rectangle_one"></div>
        <div class="rectangle_two"></div>
        OUR FEATURED SEVICES</span
      >
    </h2>
    <p class="featured_services_description col-xl-10 offset-1 mb-5">
      Aenean ultricies iaculis cursus. Mauris enim tellus, finibus in felis
      sollicitu din iaculis dolor. Donec sollicitudin orci id efficitur dapibus.
      Aliq uamtem por ien sed condimentum fringilla. In magna elit, ultrices a
      eros it amet, iaculis hendrerit tellusn iaculis nisi, nec maximus lorem.
    </p>
    <div class="col-xl-12 d-flex flex-wrap justify-content-center">
      <featured-service
        v-for="(feature, index) in 3"
        :key="index"
      ></featured-service>
    </div>
  </div>
</template>
<script>
import featuredService from "./FeaturedService.vue";
export default {
  components: {
    "featured-service": featuredService
  }
};
</script>
<style scoped>
span {
  position: relative;
}
.rectangle_one,
.rectangle_two {
  position: absolute;
  width: 42px;
  height: 42px;
  border-radius: 6px;
  border: solid 1px #ffdd00;
}
.rectangle_one {
  top: -4px;
  left: -17px;
}
.rectangle_two {
  top: -12px;
  left: -23px;
}
.title {
  font-family: Montserrat;
  font-size: 40px;
  font-weight: 500;
  line-height: 0.6;
  color: #302e2f;

  padding: 50px 0;
}
.featured_services_description {
  font-family: Montserrat;
  font-size: 20px;
  line-height: 1.2;
  letter-spacing: normal;

  color: #302e2f;
}
</style>

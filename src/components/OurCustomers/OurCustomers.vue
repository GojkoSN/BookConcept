<template>
  <div
    id="carouselExampleControls"
    class="carousel slide d-flex flex-wrap justify-content-center pb-5"
    data-ride="carousel"
  >
    <h2 class="text-center pt-5 pb-5  col-xl-12">Our Happy Customer</h2>
    <div class="carousel-inner col-xl-8">
      <div class="carousel-item active d-flex flex-wrap col-xl-12">
        <div class="col-xl-6">
          <img
            class=""
            src="../../assets/images/ourCustomersImg/brooke-cagle-224821-unsplash.png"
            alt="First slide"
          />
        </div>
        <div class="col-xl-6 d-flex flex-wrap justify-content-center">
          <p class="col-xl-12 d-flex flex-wrap">
            Nale Lastnaem
            <span>booklover</span>
          </p>

          <p class="col-xl-12">
            Aenean ultricies iaculis cursus. Mauris enim tellus, finibus in
            felis sollicitu din iaculis dolor. Donec sollicitudin orci id
            efficitur dapibus. Aliq uamtem por ien sed condimentum fringilla. In
            magna elit, ultrices a eros it amet, iaculis hendrerit tellusn
            iaculis nisi, nec maximus lorem.
          </p>
        </div>
      </div>
      <!-- <div class="carousel-item d-flex">
        <img
          class=""
          src="../../assets/images/ourCustomersImg/brooke-cagle-224821-unsplash@2x.png"
          alt="Second slide"
        />
      </div>
      <div class="carousel-item">
        <img
          class=""
          src="../../assets/images/ourCustomersImg/brooke-cagle-224821-unsplash@3x.png"
          alt="Third slide"
        />
      </div> -->
    </div>
    <a
      class="carousel-control-prev"
      href="#carouselExampleControls"
      role="button"
      data-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a
      class="carousel-control-next"
      href="#carouselExampleControls"
      role="button"
      data-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</template>
<style scoped>
img {
  width: 350px;
  height: 350px;
  border-radius: 50%;
  object-fit: cover;
}
</style>

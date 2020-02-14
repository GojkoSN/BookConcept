<template>
  <div class="row col-8 justify-content-center p-0">
    <img
      class="col-xl-2"
      v-for="image in bookImages"
      :key="image.id"
      :src="image.image"
    />
  </div>
</template>
<script>
export default {
  data() {
    return {
      bookImages: [
        {
          image: require("../../assets/images/TopRatedBooksImg/c6qfzDo.png"),
          id: 1
        },
        {
          image: require("../../assets/images/TopRatedBooksImg/hdRBuGecopy.png"),
          id: 2
        },
        {
          image: require("../../assets/images/TopRatedBooksImg/yv2gnNU.png"),
          id: 3
        },
        {
          image: require("../../assets/images/TopRatedBooksImg/ZpD1mv0.png"),
          id: 4
        },
        {
          image: require("../../assets/images/TopRatedBooksImg/ZpD1mv0.png"),
          id: 5
        },
        {
          image: require("../../assets/images/TopRatedBooksImg/yv2gnNU.png"),
          id: 6
        }
      ]
    };
  }
};
</script>

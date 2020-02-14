<template>
  <div style="backgroundColor:white" class="container-fluid">
    <h2 class="text-center mt-5 mb-5 top_rated_title">Top Rated Books</h2>
    <div class="d-flex flex-wrap justify-content-center book_container">
      <top-rated-book></top-rated-book>
    </div>
  </div>
</template>
<script>
import topRatedBook from "./TopRatedBook";
export default {
  components: {
    "top-rated-book": topRatedBook
  }
};
</script>
<style>
.top_rated_title {
  font-family: DancingScript;
  font-size: 60px;
  font-weight: bold;
  line-height: 1.33;
  text-align: center;
  color: #414042;
}
.book_container {
  margin-bottom: 100px;
}
</style>

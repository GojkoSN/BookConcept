<template>
  <div class="app row justify-content-center">
    <landing-page></landing-page>
    <featured-services></featured-services>
    <top-rated-books></top-rated-books>
    <benefits></benefits>
    <most-popular-books></most-popular-books>
    <our-customers></our-customers>
    <concept-price></concept-price>
  </div>
</template>

<script>
import landingPage from "./components/LandingPage.vue";
import featuredServices from "./components/FeaturedServices/FeaturedServices.vue";
import topRatedBooks from "./components/topRatedBooks/TopRatedBooks";
import benefits from "./components/Benefits/Benefits.vue";
import mostPopularBooks from "./components/MostPopularBooks/MostPopularBooks.vue";
import ourCustomers from "./components/OurCustomers/OurCustomers.vue";
import conceptPrice from "./components/ConceptPrice/Price.vue";

export default {
  components: {
    "landing-page": landingPage,
    "featured-services": featuredServices,
    "top-rated-books": topRatedBooks,
    "most-popular-books": mostPopularBooks,
    "our-customers": ourCustomers,
    "concept-price": conceptPrice,
    benefits
  }
};
</script>

<style>
.app {
  background-color: hsl(0, 17%, 98%);
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>

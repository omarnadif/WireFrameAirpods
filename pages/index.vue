<template>
  <div>
    <Navbar />
    <div class="hero-section container-fluid d-flex flex-column justify-content-center align-items-center">
      <div class="row w-100">
        <div class="col-12 col-md-4 text-center">
          <div class="airpod-container airpod-container-left">
            <img src="~assets/images/left.png" class="airpod-image-large" alt="AirPod Left">
          </div>
        </div>
        <div class="col-12 col-md-4 text-center d-flex flex-column align-items-center">
          <h1 class="hero-title">AirPods 3<sup>e</sup></h1>
          <p class="hero-price">199 €</p>
          <div class="hero-buttons d-flex flex-column flex-md-row justify-content-center">
            <nuxt-link to="/achat" class="btn btn-light btn-rounded">Acheter</nuxt-link>
            <nuxt-link to="/caracteristiques" class="btn btn-outline-light">En savoir plus ></nuxt-link>
          </div>
        </div>
        <div class="col-12 col-md-4 text-center">
          <div class="airpod-container airpod-container-right">
            <img src="~assets/images/right.png" class="airpod-image-large" alt="AirPod Right">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  components: {
    Navbar: () => import('~/components/Navbar.vue')
  }
}
</script>

<style scoped>
.hero-section {
  padding: 100px 0;
  background-color: #000; 
  color: #fff; 
}

.hero-title {
  font-size: 4rem;
  font-weight: bold;
  z-index: 1;
}

.hero-price {
  font-size: 2rem;
  margin: 20px 0;
  z-index: 1;
}

.hero-buttons .btn {
  margin: 10px;
  z-index: 1;
}

.hero-buttons .btn-rounded {
  border-radius: 20px;
}

.airpod-container-left, .airpod-container-right {
  display: flex;
  justify-content: center;
}

.airpod-image-large {
  max-width: 100%;
  height: auto;
  margin-bottom: 20px;
}
</style>

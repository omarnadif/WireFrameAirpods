<template>
    <div>
      <Navbar />
      <section id="achat" class="text-center my-5">
        <h1>Achat</h1>
        <div class="container">
          <div class="row align-items-center">
            <div class="col-md-6 text-left">
              <h2>AirPods</h2>
              <h3>(3<sup>e</sup> génération) avec Boîtier de charge MagSafe</h3>
              <p class="livraison-info">
                <img src="~assets/images/camion.png" alt="Delivery Icon" class="icon"> Livraison : En stock<br>
                Livraison gratuite<br>
                <a href="#" class="link">Afficher les dates de livraison</a>
              </p>
              <p class="retrait-info">
                <img src="~assets/images/store.png" alt="Pickup Icon" class="icon"> Retrait :<br>
                <a href="#" class="link">Vérifier la disponibilité</a>
              </p>
              <nuxt-link to="/confirmation" class="btn btn-primary btn-lg">Buy</nuxt-link>
            </div>
            <div class="col-md-6 text-center">
              <img src="~assets/images/airpodsOpen.png" alt="AirPods" class="product-image">
            </div>
          </div>
        </div>
      </section>
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
  #achat {
    padding: 50px 0;
    background-color: #000; 
    color: #fff;
  }
  
  #achat h1 {
    font-size: 4rem; 
    margin-bottom: 40px;
  }
  
  #achat h2 {
    font-size: 2rem;
  }
  
  #achat h3 {
    font-size: 1.5rem;
    margin-bottom: 20px;
  }
  
  .livraison-info, .retrait-info {
    font-size: 1rem;
    margin-bottom: 20px;
  }
  
  .icon {
    width: 20px;
    margin-right: 10px;
  }
  
  .link {
    color: #007bff;
    text-decoration: none;
  }
  
  .link:hover {
    text-decoration: underline;
  }
  
  .product-image {
    max-width: 100%;
    height: auto;
  }
  
  .btn-primary {
    background-color: #007bff;
    border-color: #007bff;
    color: #fff;
  }
  
  .btn-block {
    width: 100%;
    max-width: 300px;
  }
  </style>
  
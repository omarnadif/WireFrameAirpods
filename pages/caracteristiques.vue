<template>
    <div>
      <Navbar />
      <section id="caracteristiques" class="text-center my-5">
        <h2>Caractéristiques</h2>
        <img src="~assets/images/boxAirpods.png" alt="AirPods" class="my-3">
        <h3>AirPods</h3>
        <p>3<sup>e</sup> génération</p>
        <div class="row">
          <div class="col-md-3">
            <p><img src="~assets/images/spacial.png" alt="Spatial Audio Icon"><br>Audio spatial personnalisé avec suivi dynamique des mouvements de la tête</p>
          </div>
          <div class="col-md-3">
            <p><img src="~assets/images/airpodsIcon.png" alt="Charging Case Icon"><br>Boîtier de charge Lightning ou Boîtier de charge MagSafe</p>
          </div>
          <div class="col-md-3">
            <p><img src="~assets/images/water.png" alt="Water Resistant Icon"><br>Résistance à la transpiration et à l’eau</p>
          </div>
          <div class="col-md-3">
            <p><img src="~assets/images/6h.png" alt="Battery Life Icon"><br>Jusqu’à 6 h d’écoute sur une seule charge</p>
          </div>
        </div>
      </section>
    </div>
  </template>
  
  <script>
  export default {
    components: {
    }
  }
  </script>
  
  <style scoped>
  #caracteristiques {
    background-color: #000; 
    color: #fff; 
  }
  
  #caracteristiques h2 {
    font-size: 3rem;
    margin-bottom: 30px;
  }
  
  #caracteristiques img {
    max-width: 150px;
    margin: 20px 0;
  }
  
  #caracteristiques .row {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 30px;
  }
  
  #caracteristiques .col-md-3 {
    margin-bottom: 20px;
  }
  
  #caracteristiques .btn {
    margin-top: 30px;
  }
  </style>
  
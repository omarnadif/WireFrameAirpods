<template>
    <div>
      <Navbar />
      <section id="technologies" class="text-center">
        <h1>Technologies</h1>
        <div class="container">
          <div class="row">
            <div class="col-12">
              <h3>Technologie audio</h3>
              <ul class="text-left">
                <li>Transducteur Apple à haute excursion conçu sur mesure</li>
                <li>Amplificateur à gamme dynamique élevée conçu sur mesure</li>
                <li>Audio spatial personnalisé avec suivi dynamique des mouvements de la tête</li>
                <li>Égalisation adaptative</li>
              </ul>
            </div>
          </div>
          <div class="row mt-5">
            <div class="col-12">
              <h3>Commandes</h3>
              <ul class="text-left">
                <li><span class="dot"></span> Appuyer une fois pour lancer la lecture de vos contenus multimédias ou les mettre en pause</li>
                <li><span class="dot"></span> Appuyer une fois pour répondre à un appel ou couper et réactiver le micro</li>
                <li><span class="dot"></span><span class="dot"></span> Appuyer deux fois pour raccrocher</li>
                <li><span class="dot"></span><span class="dot"></span> Appuyer deux fois pour passer au morceau suivant</li>
                <li><span class="dot"></span><span class="dot"></span><span class="dot"></span> Appuyer trois fois pour revenir en arrière</li>
                <li><span class="dot-long"></span> Appuyer de façon prolongée pour s'adresser à Siri</li>
                <li> <img src="~assets/images/micro.png" alt="Microphone Icon" class="micro-icon"> Dire « Dis Siri » pour, par exemple, écouter un morceau, passer un appel ou obtenir un itinéraire
                 
                </li>
              </ul>
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
  #technologies {
    padding: 20px 0;
    background-color: #000; 
    color: #fff; 
  }
  
  #technologies h1 {
    font-size: 4rem; 
    margin-bottom: 40px;
  }
  
  #technologies h3 {
    font-size: 2rem; 
  }
  
  #technologies ul {
    list-style-type: none;
    padding-left: 0;
  }
  
  #technologies li {
    font-size: 1.4rem; 
    margin-bottom: 15px;
  }
  
  .dot {
    height: 12px;
    width: 12px;
    background-color: limegreen;
    border-radius: 50%;
    display: inline-block;
    margin-right: 10px;
  }
  .dot-long {
    height: 12px;
    width: 50px;
    background-color: limegreen;
    border-radius: 30%;
    display: inline-block;
    margin-right: 10px;
  }
  
  .micro-icon {
    height: 20px; 
    margin-left: 20px;
  }
  </style>
  
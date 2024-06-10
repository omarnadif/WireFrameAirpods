<template>
  <div>
    <Navbar />
    <section id="fonctionnalite" class="text-center my-5">
      <h1>Fonctionnalité</h1>
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-6 col-md-2 fonctionnalite-item">
            <div class="card bg-white text-dark">
              <div class="card-body d-flex flex-column align-items-center justify-content-center">
                <img src="~assets/images/logo_accessibility.png" alt="Accessibilité" class="fonctionnalite-icon">
                <p class="card-text">Accessibilité</p>
              </div>
            </div>
          </div>
          <div class="col-6 col-md-2 fonctionnalite-item">
            <div class="card bg-white text-dark">
              <div class="card-body d-flex flex-column align-items-center justify-content-center">
                <img src="~assets/images/logo_audio_sharing.png" alt="Partage audio" class="fonctionnalite-icon">
                <p class="card-text">Partage audio</p>
              </div>
            </div>
          </div>
          <div class="col-6 col-md-2 fonctionnalite-item">
            <div class="card bg-white text-dark">
              <div class="card-body d-flex flex-column align-items-center justify-content-center">
                <img src="~assets/images/logo_spatial.png" alt="Audio spatial" class="fonctionnalite-icon">
                <p class="card-text">Audio spatial</p>
              </div>
            </div>
          </div>
          <div class="col-6 col-md-2 fonctionnalite-item">
            <div class="card bg-white text-dark">
              <div class="card-body d-flex flex-column align-items-center justify-content-center">
                <img src="~assets/images/logo_siri.png" alt="Siri" class="fonctionnalite-icon">
                <p class="card-text">Siri</p>
              </div>
            </div>
          </div>
          <div class="col-6 col-md-2 fonctionnalite-item">
            <div class="card bg-white text-dark">
              <div class="card-body d-flex flex-column align-items-center justify-content-center">
                <img src="~assets/images/logo_auto.png" alt="Basculement auto" class="fonctionnalite-icon">
                <p class="card-text">Basculement auto</p>
              </div>
            </div>
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
#fonctionnalite {
  padding: 50px 0;
  background-color: #000; 
  color: #fff; 
}

#fonctionnalite h1 {
  font-size: 4rem;
  margin-bottom: 40px;
}

.fonctionnalite-item {
  text-align: center;
  margin-bottom: 30px;
}

.fonctionnalite-icon {
  max-width: 100px;
  margin-bottom: 10px;
}

.card {
  width: 100%; 
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 20px; 
  border: none; 
  border-radius: 10px; 
  background-color: #fff; 
}

.card-body {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  height: 100%; 
}

.card-text {
  margin-top: 10px;
  color: #000; 
}
</style>

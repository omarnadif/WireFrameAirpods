<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-black">
      <div class="container">
        <nuxt-link to="/" class="navbar-brand">
          <img src="~assets/images/appleLogo.png" alt="Apple Logo" width="30">
        </nuxt-link>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-center" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <nuxt-link to="/" class="nav-link">Home</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="/caracteristiques" class="nav-link">Caractéristiques</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="/technologies" class="nav-link">Technologies</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="/fonctionnalite" class="nav-link">Fonctionnalité</nuxt-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </template>
  
  <style scoped>
  .navbar {
    padding: 1rem 0;
    background-color: #000;
  }
  
  .navbar-brand {
    margin-right: 1rem;
  }
  
  .navbar-nav {
    align-items: center;
  }
  
  .navbar-nav .nav-link {
    color: #fff !important;
    margin: 0 1rem;
  }
  </style>
  
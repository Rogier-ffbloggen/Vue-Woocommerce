<template>
    <section class="hero is-primary is-medium">
        <div class="hero-head pt-5">
            <div class="container">
            <p class="title">
                Romper Online Winkel
            </p>
            <p class="subtitle">
                Rompertjes met leuke cartoon plaatjes compleet met bijpassende doos.
            </p>
            </div>
        </div>

        <div class="hero-body pt-6">
            
                <div class="container">
                    <figure class="image is-3by2">
                    <img alt="Rompertjes Home" src="../assets/Hero.jpg">
                    </figure>
                </div>
        </div>
            
        <div class="hero-foot pb-2">
            <nav class="navbar">
            <div class="container">
                <div class="navbar-brand">
                <router-link to="/" class="navbar-item">
                    <font-awesome-icon icon="home" />
                    <strong class="ml-1">Home</strong>
                </router-link>
                    <a role="button" class="navbar-burger" 
                    data-target="navbarMenuHeroB" aria-label="menu" aria-expanded="false">
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                    </a>
                </div>
                <div id="navbarMenuHeroB" class="navbar-menu">
                <div class="navbar-start">
                    <router-link to="/afrekenen" class="navbar-item">
                        <strong class="ml-1">Afrekenen</strong>
                    </router-link>
                    <router-link to="/info" class="navbar-item">
                        <strong>Mijn account</strong>
                    </router-link>
                    <router-link to="/winkelmand" class="navbar-item">
                        <strong>Winkelmand</strong>
                    </router-link>
                </div>
                <div class="navbar-end pt-3">
                    <b-tooltip label="Geen producten in je winkelmand."
                        position="is-bottom" multilined>
                            <router-link to="/winkelmand">
                            <div class="buttons">
                                <b-button 
                                label="€0.00" 
                                type="is-dark" />
                                <font-awesome-icon class="ml-5" icon="shopping-basket" />
                            </div>
                            </router-link>
                    </b-tooltip>
                </div>
                </div>
            </div>
            </nav>
        </div>
    </section>
</template>

<script>
document.addEventListener('DOMContentLoaded', () => {

  // Get all "navbar-burger" elements
  const $navbarBurgers = Array.prototype.slice.call(document.querySelectorAll('.navbar-burger'), 0);

  // Check if there are any navbar burgers
  if ($navbarBurgers.length > 0) {

    // Add a click event on each of them
    $navbarBurgers.forEach( el => {
      el.addEventListener('click', () => {

        // Get the target from the "data-target" attribute
        const target = el.dataset.target;
        const $target = document.getElementById(target);

        // Toggle the "is-active" class on both the "navbar-burger" and the "navbar-menu"
        el.classList.toggle('is-active');
        $target.classList.toggle('is-active');

      });
    });
  }

});
</script>


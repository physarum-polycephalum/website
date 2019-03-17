<template>
  <div>
    <div class="main-container">
      <section class="cover height-100 imagebg parallax" data-overlay="4">
        <div class="background-image-holder">
          <img alt="background" src="img/background.jpg" />
        </div>
        <div class="container pos-vertical-center">
          <div class="row">
            <div class="col-md-9 col-lg-7">
              <div class="typed-headline">
                <span class="h1 typed-text typed-text--cursor" data-typed-strings="Un être hors du commun : Le physarum polycephalum"></span>
              </div>
              <p class="lead">
                Est-il possible modéliser le comportement d'un être vivant sous forme informatique ?
              </p>
            </div>
          </div>
        </div>
      </section>

      <story></story>
      <experiences></experiences>
      <modelling></modelling>

      <section class="page-navigator">
        <ul>
          <li>
            <a href="#histoire" class="inner-link" data-title="Histoire et fonctionnement"></a>
          </li>
          <li>
            <a href="#experimentations" class="inner-link" data-title="Expérimentations"></a>
          </li>
          <li>
            <a href="#modelisation" class="inner-link" data-title="Modélisation"></a>
          </li>
        </ul>
      </section>

      <footer class="footer-7 text-center-xs bg--secondary">
        <div class="container">
          <div class="row">
            <div class="col-md-6">
              Réalisé par Clément Polycarpe, Bernard-Raphaël Mermet et Hugo Lageneste
            </div>
          </div>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
  import Story from './components/Story.vue'
  import Experiences from './components/Experiences.vue'
  import Modelling from './components/Modelling.vue'

  export default {
    name: 'app',
    components: {
      Experiences,
      Story,
      Modelling
    }
  }
</script>
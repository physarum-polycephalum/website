<template>
  <div>
    <div class="nav-container">
      <div class="bar bar--sm visible-xs">
        <div class="container">
          <div class="row">
            <div class="col-9 col-md-10 text-right">
              <a href="#" class="hamburger-toggle" data-toggle-class="#menu1;hidden-xs">
                <i class="icon icon--sm stack-interface stack-menu"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
      <nav id="menu1" class="bar bar--sm bar-1 hidden-xs bar--absolute bar--transparent">
        <div class="container">
          <div class="row">
            <div class="col-lg-1 col-md-2 hidden-xs">
              <h1 class="color--primary">TPE</h1>
            </div>
          </div>
        </div>
      </nav>
    </div>
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
      <footer class="space--sm footer-2 ">
        <div class="container">
          <div class="col-md-6">
            Réalisé par Clément Polycarpe, Bernard-Raphaël Mermet et Hugo Lageneste
          </div>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
  import Story from './components/Story.vue'
  import Experiences from './components/Experiences.vue'

  export default {
    name: 'app',
    components: {
      Experiences,
      Story
    }
  }
</script>
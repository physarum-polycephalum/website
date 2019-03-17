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
            <div class="col-lg-11 col-md-12 text-right text-left-xs text-left-sm">
              <div class="bar__module">
                <a class="btn btn--sm inner-link type--uppercase" href="#histoire-et-fonctionnement">
                  <span class="btn__text">
                    Histoire et fonctionnement
                  </span>
                </a>
                <a class="btn btn--sm inner-link type--uppercase" href="#experimentations">
                  <span class="btn__text">
                    Expérimentations
                  </span>
                </a>
                <a class="btn btn--sm inner-link type--uppercase" href="#modelisation">
                  <span class="btn__text">
                    Modélisation
                  </span>
                </a>
              </div>
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

export default {
  name: 'app',
  components: {
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

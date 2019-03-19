<script src="../../../checker/main.js"></script>
<template>
  <div id="experimentations">
    <section class="switchable feature-large">
      <div class="container">
        <div class="row justify-content-around">
          <div class="col-md-6 col-lg-5">
            <div class="switchable__text">
              <h2>Expérimentations avec le Blob</h2>
              <p class="lead">
                Nous avons utilisé DesignSpark pour modéliser notre labyrinthe en 3D. Puis l'avons imprimé en 3 heures.
              </p>
            </div>
          </div>
          <div class="col-md-6">
            <img alt="Image" class="border--round" src="img/conception-labyrinthe.png" />
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <div class="feature">
              <img alt="Image" src="img/labyrinthe-0.png" class="border--round" />
              <h4>H-0 Début de l'expérience</h4>
              <p>
                Morceaux de blob disposés dans le labyrinthe.
              </p>
            </div>
          </div>
          <div class="col-md-4">
            <div class="feature">
              <img alt="Image" src="img/labyrinthe-1.png" class="border--round" />
              <h4>H-6 Expérience en cours</h4>
              <p>
                Le blob a recouvert la quasi-totalité du labyrinthe...
              </p>
            </div>
          </div>
          <div class="col-md-4">
            <div class="feature">
              <img alt="Image" src="img/labyrinthe-2.png" class="border--round" />
              <h4>H-12 Expérience terminée</h4>
              <p>
                Le blob s'est concentré sur le chemin le plus court.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
  export default {
    name: 'Experiences'
  }
</script>
<template>
  <div id="histoire">
    <section class="switchable feature-large">
      <div class="container">
        <div class="row justify-content-around">
          <div class="col-md-6">
            <img alt="Image" class="border--round" src="img/blob-nature.jpg" />
          </div>
          <div class="col-md-6 col-lg-5">
            <div class="switchable__text">
              <h2>Histoire et fonctionnement du Blob</h2>
              <p class="lead">
                Le physarum polycephalum est une espèce qui se situe principalement dans les sous bois ou dans les zones humides.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="feature-large feature-large-2 bg--secondary">
      <div class="container">
        <div class="row justify-content-around">
          <div class="col-md-4 col-lg-3">
            <h3>Préparation du Blob</h3>
            <p class="lead">
              Nous avons cultivé le physarum polycephalum en coulant premièrement une gélose dans une boîte de pétri. Ensuite poser la sclérote sur la gélose avec des flocons d'avoine.
            </p>
          </div>
          <div class="col-md-4 col-lg-4">
            <img alt="Image" class="border--round box-shadow-wide" src="img/blob-preparation.png" />
          </div>
          <div class="col-md-4 col-lg-2">
            <hr class="short" />
            <p>
              Voici ici notre première culture de physarum polycephalum après 1 heure de développement
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="cover height-80 imagebg text-center" data-overlay="6">
      <div class="background-image-holder">
        <img alt="background" src="img/cytoplasme-blob.png" />
      </div>
      <div class="container pos-vertical-center">
        <div class="row">
          <div class="col-md-6">
            <span class="h1">Le ”sang“ du blob</span>
            <div class="modal-instance block">
              <div class="video-play-icon video-play-icon--sm modal-trigger"></div>
              <span>
                <strong>Voir le cytoplasme en action</strong>
              </span>
              <div class="modal-container">
                <div class="modal-content bg-dark" data-width="60%" data-height="60%">
                  <iframe width="560" height="315" src="https://www.youtube.com/embed/pO48XNqT6l8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
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
    name: 'Story'
  }
</script>

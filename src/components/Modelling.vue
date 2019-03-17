<template>
  <div id="modelisation">
    <section class="feature-large feature-large-2 bg--secondary">
      <div class="container">
        <div class="row justify-content-around">
          <div class="col-md-4 col-lg-4">
            <h3>Modélisation du comportement du Blob</h3>
            <p class="lead">
              Nous avons utilisé l'algorithme A*. Son but est de trouver le “coût” de parcours le plus faible, minimisant <strong>f(n)=g(n)+h(n)</strong>.
            </p>
          </div>
          <div class="col-md-4 col-lg-4">
            <img alt="Image" class="border--round box-shadow-wide" src="img/algorithme-exemple.png" />
          </div>
          <div class="col-md-4 col-lg-2">
            <hr class="short" />
            <p>
              Ici nous avons en vert le nœud de départ, en rouge celui d'arrivée ainsi que la valeur de f pour chacun des nœuds parcourus
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="imagebg">
      <div class="background-image-holder">
        <img alt="background" src="img/screenshot-webstorm.png" />
      </div>
      <div class="container">
        <div class="row justify-content-end">
          <div class="col-md-7 col-lg-5">
            <div class="boxed boxed--lg border--round bg--white">
              <div class="col-lg-10 mx-auto col-md-12">
                <h3>Programmation</h3>
                <p class="lead">
                  Nous avons programmé en utilisant le langage JavaScript accompagné de l'environnement Node.js. L'utilisation de Git nous a permis de travailler à trois.
                </p>
                <hr class="short" />
                <p>
                  Ci-contre voici une capture d'écran de l'IDE (EID en français) WebStorm que nous avons utilisé pour concevoir notre programme.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <div class="feature feature-5 boxed boxed--lg boxed--border">
              <img alt="Image" height="100px" class="border--round box-shadow-wide" src="img/labyrinthe-programme.png" />
              <div class="feature__body">
                <h5>Labyrinthe dessiné</h5>
                <p>
                  Ici le labyrinthe simplifé à l'état de pixels noirs pour représenter les murs, blancs pour représenter les espaces vides et rouges pour les extrémités.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-6">
            <div class="feature feature-5 boxed boxed--lg boxed--border">
              <img alt="Image" height="100px" class="border--round box-shadow-wide" src="img/labyrinthe-programme-fini.png" />
              <div class="feature__body">
                <h5>Labyrinthe résolu</h5>
                <p>
                  Après l'éxécution de notre programme cette image est générée, avec en bleu le trajet le plus court déterminé par l'algorithme.
                </p>
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
    name: 'Modelling'
  }
</script>

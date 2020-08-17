<template>
  <div id="app">
    <link href="https://fonts.googleapis.com/css2?family=Alata&display=swap" rel="stylesheet">

    <b-jumbotron header="Cornelia Staub" lead="Gesundheitsberaterin GGB">
      <!--<b-nav pills>
    <b-nav-item active>Startseite</b-nav-item>
    <b-nav-item>Aktuell</b-nav-item>
    <b-nav-item>Rezepte</b-nav-item>
  </b-nav>-->

      <br>

      <div>
        <b-container fluid>
          <b-row>
            <p style="margin-left: 0%; font-size: 1.5rem;">Gesünder essen</p>
          </b-row>
          <b-row>
            <p style="margin-left: 5%; font-size: 1.5rem;">Mehr bewegen</p>
          </b-row>
          <b-row>
            <p style="margin-left: 10%; font-size: 1.5rem;">Zur Ruhe kommen</p>
          </b-row>
          <b-row>
            <h2>Über mich</h2>
          </b-row>
          <b-row>
            <i class="fas fa-apple-alt"></i>
            <ul>
              <li>1966 in Esslingen geboren</li>
              <li>verheiratet und 2 erwachsene Kinder</li>
              <li>gelernte Bürokauffrau</li>
              <li>Übungsleiterin Aerobic</li>
              <li>Trainerin B Prävention Erwachsene</li>
              <li>Rückentrainerin</li>
              <li>Pilatestrainerin</li>
              <li>Beckenbodentrainerin</li>
              <li>Achtsamkeitstrainerin</li>
            </ul>
          </b-row>
          <b-row>
            <h2>Rezept Frischkornbrei nach Prof. Kollath</h2>
          </b-row>
          <b-row>
            <b-col>
              <b-img src="./assets/imgs/frischkornbrei.jpg" fluid alt="Rezept Frischkornbrei nach Prof. Kollath"
              style="padding-top: 10px">
              </b-img>
            </b-col>
            <b-col cols="9">
              <p>
                Es wird aus Roggen oder Weizen oder einer beliebigen Getreideart oder Getreidemischung hergestellt.
              </p>
              <p>
                Dazu werden 3 Esslöffel (etwa 50 g) Getreide in einer Getreidemühle, in einen Mixapparat oder einer
                Kaffeemühle grob geschrotet.
              </p>
              <p>
                Das Mahlen muss jedes Mal frisch vor der Zubereitung vorgenommen werden.
              </p>
              <p>
                Nicht auf Vorrat mahlen! Dabei spielt es keine Rolle, ob die Getreidemühle mit Mahlsteinen oder einem
                Stahlwerk arbeitet.
              </p>
              <p>
                Das gemahlene Getreide wird mit ungekochtem, kaltem Leitungswasser zu einem Brei gerührt und
                5-12 Stunden stehen gelassen. Die Wassermenge ist so berechnet, dass nach Quellung nichts weggegossen zu
                werden braucht. Danach wird der Brei tischfertig gemacht durch Zusatz von frischem Obst (je nach
                Jahreszeit),
                Zitronensaft, 1-2 Esslöffel Sahne und geriebenen Nüssen.
              </p>
              <p>
                Solange verfügbar, sollte man immer einen Apfel hinein reiben und sogleich untermischen, bevor er braun
                wird.
                Der geriebene Apfel macht den Frischkornbrei luftig und wohlschmeckend.
                Es ist ohne Belang, zu welcher Tageszeit dieses Gericht genossen wird.

              </p>
            </b-col>

          </b-row>
        </b-container>

      </div>
    </b-jumbotron>
  </div>
</template>

<script>
  export default {
    name: 'App',
    components: {}
  }
</script>

<style>
  #app {
    font-family: 'Alata', sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
    margin: 60px;
    margin-top: 60px;
  }

  h2 {
    margin-top: 30px;
  }

  li {
    font-size: 1.2rem;
  }

  .lead {
    font-size: 3rem;
  }
</style>
<template>
  <div id="app">
    <link href="https://fonts.googleapis.com/css2?family=Alata&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css">

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
            <b-col>
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
              <p class="text" style="font-weight: 800;">ärztlich geprüfte Gesundheitsberaterin GGB</p>
            </b-col>
            <b-col>
              <b-img src="./assets/imgs/conny.jpg" fluid alt="Cornelia Straub" style="padding-top: 10px; height: 40%" />
            </b-col>
          </b-row>

          <b-row>
            <b-col>
              <h2>Ich biete an</h2>
            </b-col>
            <b-col>
              <h2>Interesse</h2>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <ul>
                <li>Gesundheitsberatung</li>
                <li>Ernährungseinzelberatung</li>
                <li>Einkaufsbegleitung</li>
                <li>Vorträge</li>
                <li>Meditation</li>
                <li>Rückentraining</li>
                <li>Pilates</li>
              </ul>
            </b-col>
            <b-col>
              <p class="text">Wir sind eine Körper-Geist-Seele Einheit.
                Mir ist es ein Anliegen, interessierten Menschen meine Erfahrungen und das Wissen über die Zusammenhänge
                der eigenen Lebensweise und der Krankheit bzw. Gesundheit weiterzugeben.
                Und das neu Erlernte auszuprobieren.
              </p>
            </b-col>
          </b-row>
          <b-row>
            <b-col>
              <b-img src="./assets/imgs/salat.jpg" fluid alt="Salat" style="padding-top: 10px; height: 40%" />
            </b-col>
            <b-col>
              <b-img src="./assets/imgs/hauptgericht.jpg" fluid alt="Hauptgericht"
                style="padding-top: 10px; height: 40%" />
            </b-col>
            <b-col>
              <b-img src="./assets/imgs/nachtisch.jpg" fluid alt="Nachtisch" style="padding-top: 10px; height: 40%" />
            </b-col>
          </b-row>

          <b-row>
            <h2>Ernährungsbedingte Zivilisationskrankheiten nach Dr. Max Otto Bruker</h2>
          </b-row>
          <b-row>
            <ul>
              <li>Gebissverfall, Zahnkaries, Parodontose und Zahnfehlstellungen</li>
              <li>Erkrankungen des Bewegungsapparates, so genannte rheumatische Erkrankungen</li>
              <li>Alle Stoffwechselkrankheiten wie Übergewicht und Zuckerkrankheit</li>
              <li>Die meisten Erkrankungen der Verdauungsorgane wie Stuhlverstopfung</li>
              <li>Gefäßerkrankungen wie Arteriosklerose, Herzinfarkt, Schlaganfall und Thrombosen</li>
              <li>Mangelnde Infektabwehr</li>
              <li>Die meisten der so genannten Allergien</li>
              <li>Manche organische Erkrankungen des Nervensystems, z.B. MS</li>
              <li>Auch an der Entstehung des Krebses ist die Fehlernährung in erheblichem Maße beteiligt</li>
            </ul>
          </b-row>

          <b-row>
            <h2>Kontakt</h2>
          </b-row>
          <b-row class="text">Mail: <a href="mailto:info@gesundheitsberaterin-esslingen.de"> info@gesundheitsberaterin-esslingen.de</a></b-row>
          <b-row class="text">Telefon: <a href="tel:+49711 367728"> 0711 367728</a></b-row>
          <b-row class="text">Weitere Informationen bei der Gesellschaft für Gesundheitsberatung GGB e.V. in 56112 Lahnstein</b-row>

          <b-row>
            <h2>Rezept Frischkornbrei nach Prof. Kollath</h2>
          </b-row>
          <b-row style="padding-top:10px;">
            <b-col>
              <b-img src="./assets/imgs/frischkornbrei.jpg" fluid alt="Rezept Frischkornbrei nach Prof. Kollath"
                style="padding-top: 10px">
              </b-img>
            </b-col>
            <b-col cols="8">
              <p class="text">
                Es wird aus Roggen oder Weizen oder einer beliebigen Getreideart oder Getreidemischung hergestellt.
              </p>
              <p class="text">
                Dazu werden 3 Esslöffel (etwa 50 g) Getreide in einer Getreidemühle, in einen Mixapparat oder einer
                Kaffeemühle grob geschrotet.
              </p>
              <p class="text">
                Das Mahlen muss jedes Mal frisch vor der Zubereitung vorgenommen werden.
              </p>
              <p class="text">
                Nicht auf Vorrat mahlen! Dabei spielt es keine Rolle, ob die Getreidemühle mit Mahlsteinen oder einem
                Stahlwerk arbeitet.
              </p>
              <p class="text">
                Das gemahlene Getreide wird mit ungekochtem, kaltem Leitungswasser zu einem Brei gerührt und
                5-12 Stunden stehen gelassen. Die Wassermenge ist so berechnet, dass nach Quellung nichts weggegossen zu
                werden braucht. Danach wird der Brei tischfertig gemacht durch Zusatz von frischem Obst (je nach
                Jahreszeit),
                Zitronensaft, 1-2 Esslöffel Sahne und geriebenen Nüssen.
              </p>
              <p class="text">
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
    margin-top: 50px;
  }

  ul {
    list-style: none;
    padding: 0;
  }

  li {
    padding-left: 1.3em;
    font-size: 1.2rem;
  }

  li:before {
    content: "\f5d1";
    /* FontAwesome Unicode */
    font-family: FontAwesome;
    display: inline-block;
    margin-left: -1.3em;
    /* same as padding-left set on li */
    width: 1.3em;
    /* same as padding-left set on li */
  }

  .lead {
    font-size: 3rem;
  }

  .text {
    font-size: 1.25rem;
  }
</style>
<template>
  <div id="App">
    <!-- first Column -->
    <div class="presentation">
      <!-- Avatar -->
      <div class="presentation__img">
        <figure>
          <img src="../static/joel2.jpg" width="250" />
        </figure>
      </div>
      <!-- /Avatar -->
      <!-- little info -->
      <div class="presentation__info">
        <div class="presentation__info_text">
          <p>Joel Gustavo Suarez Rodriguez. Desarrollador web Frontent
            Santiago de Cali
          </p>
        </div>
        <!-- menu -->
        <div class="presentation__info_nav">
          <nav class="menu" id="menu">
            <ul class="menu__list">
              <li><a href="#">Trabajos</a></li>
              <li><a href="#">Certificaciones</a></li>
              <li><a href="#" target="">Conocimientos</a></li>
              <li><a href="#" target="">Bio y Contacto</a></li>
            </ul>
          </nav>
        </div>
        <!-- /menu -->
        
        <!-- social media -->
        <div class="presentation__info_social">
          <div class="item item1">
            <figure class="logo">
              <img src="../static/github.png" width="25" />
            </figure>
          </div>
          <div class="item item2">
            <figure class="logo">
              <img src="../static/linkedin.png" width="25" />
            </figure>
          </div>
          <div class="item item3">
            <figure class="logo">
              <img src="../static/twitter.png" width="25" />
            </figure>
          </div>
        </div>
        <!-- /social media -->

      </div>
      <!-- /little info -->
    </div>

    <!-- Second Column  -->
    <div class="layout">
      <div class="layout__title">
        <h2>Trabajos</h2>
      </div>
      <!-- works -->
      <section class="layout__works">
        <article class="layout__works_item">
          <div class="layout_works_item_img">
            <figure>
              <img src="../static/jetsetmobile.png" width="250" />
            </figure>
          </div>
          <div class="layout_works_item_description">
            <aside class="layout_works_item_description">
              <span>Tecnologias: Vuejs, Firebase</span>
              <span>Url: jetsetmobile.info</span>
              <span>Github:</span>
            </aside>
          </div>
        </article>
        <article class="layout__works_item">
          <div class="layout_works_item_img">
            <figure>
              <img src="../static/meetupsapp.png" width="250" />
            </figure>
          </div>
          <div class="layout_works_item_description">
            <aside class="layout_works_item_description">
              <span>Tecnologias: Vuejs, Firebase</span>
              <span>Url: jetsetmobile.info</span>
              <span>Github:</span>
            </aside>
          </div>
        </article>
        <article class="layout__works_item">
          <div class="layout_works_item_img">
            <figure>
              <img src="../static/exampleshop.png" width="250" />
            </figure>
          </div>
          <div class="layout_works_item_description">
            <aside class="layout_works_item_description">
              <span>Tecnologias: Bootstrap, jquery</span>
              <span>Url: jetsetmobile.info</span>
              <span>Github:</span>
            </aside>
          </div>
        </article>
        <article class="layout__works_item">
          <div class="layout_works_item_img">
            <figure>
              <img src="../static/rockatpark.png" width="250" />
            </figure>
          </div>
          <div class="layout_works_item_description">
            <aside class="layout_works_item_description">
              <span>Tecnologias: Foundation, jquery</span>
              <span>Url: jetsetmobile.info</span>
              <span>Github:</span>
            </aside>
          </div>
        </article>
        <article class="layout__works_item">
          <div class="layout_works_item_img">
            <figure>
              <img src="../static/invie.png" width="250" />
            </figure>
          </div>
          <div class="layout_works_item_description">
            <aside class="layout_works_item_description">
              <span>Tecnologias: HTML5, CSS3, jquery</span>
              <span>Url: jetsetmobile.info</span>
              <span>Github:</span>
            </aside>
          </div>
        </article>
      </section>
      <!-- /works -->
      <div class="layout__title">
        <h2>Certificados</h2>
      </div>
      <!-- certificados -->
      <div class="layout__certs">
        <article class="layout__certs_item">
          <div class="layout__certs_item_img">
            <figure>
              <img src="../static/javascript.png" width="250" />
            </figure>
          </div>
          
        </article>
        <article class="layout__certs_item">
          <div class="layout__certs_item_img">
            <figure>
              <img src="../static/postcss.png" width="250" />
            </figure>
          </div>
          
        </article>
        <article class="layout__certs_item">
          <div class="layout__certs_item_img">
            <figure>
              <img src="../static/responsive.png" width="250" />
            </figure>
          </div>
          
        </article>
        <article class="layout__certs_item">
          <div class="layout__certs_item_img">
            <figure>
              <img src="../static/vue.png" width="250" />
            </figure>
          </div>
          
        </article>
        <article class="layout__certs_item">
          <div class="layout__certs_item_img">
            <figure>
              <img src="../static/git.png" width="250" />
            </figure>
          </div>
          
        </article>
        <article class="layout__certs_item">
          <div class="layout__certs_item_img">
            <figure>
              <img src="../static/desarrollo.png" width="250" />
            </figure>
          </div>
          
        </article>
        <article class="layout__certs_item">
          <div class="layout__certs_item_img">
            <figure>
              <img src="../static/postcss.png" width="250" />
            </figure>
          </div>
          
        </article>
      </div>
      <!-- /certificados -->

      <!-- conocimientos -->
      <div class="layout__title">
        <h2>Conocimientos</h2>
      </div>
      <div class="layout__knowledge">
        <div class="layout__knowledge_col">
          <h3>Maquetacion Web</h3>
          <ul class="layout__knowledge_col_features">
            <li>HTML5</li>  
            <li>CSS3</li>  
            <li>Flexbox</li>  
            <li>Css-grid</li>  
          </ul>  
        </div>
        <div class="layout__knowledge_col">
          <h3>Frameworks frontend</h3>
          <ul class="layout__knowledge_col_features">
            <li>Vuejs</li>  
            <li>Vuetify</li>  
            <li>Bootstrap</li>  
            <li>Foundation</li>  
          </ul> 
        </div>
        <div class="layout__knowledge_col">
          <h3>Backend</h3>
          <ul class="layout__knowledge_col_features">
            <li>Consumo ApiRest con express.js</li>  
            <li>CRUD con Firebase.</li>  
          </ul> 
        </div>
      </div>  

    
    <!-- /conocimientos --> 

    <!-- Bio y contacto -->
      <div class="layout__title">
        <h2>Trabajos</h2>
      </div>
      <div class="layout__info">
        <div class="layout__info__bio">
          <div>
            <h4>Nombre: Joel Gustavo Suarez Rodriguez</h4>
          </div>
          <div>
            <h4>Cedula de identidad: 1.126.427.611</h4>
          </div>
          <div class="layout__info__bio_studies">
            <h4>Estudios Universitarios:</h4>
            <p>
              Ingenieria de Sistemas en ULA Venezuela (5to Semestre).
              Estuadiante activo en Platzi.com.
            </p>
          </div>
        </div>
        <div class="layout__info__contact">
          <div>
            <h4>Correo: joelsuarez.1101@gmail.com.</h4>
          </div>
          <div>
            <h4>telefono: +57 322-7632472.</h4>
          </div>
        </div>
      </div>
    <!-- /Bio y contacto -->
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
  html {
    box-sizing: border-box;
  }

  *, *:before, *:after {
    box-sizing: inherit;
  }

  body {
    margin: 0 0;
  }

  :root {
    box-sizing: border-box;
    font-family: sans-serif;
    margin: 0 0;
    background-image: linear-gradient(260deg, #2376ae 0%, #c16ecf 100%);
  }

  #App {
    border:3px solid green;
    height:100vh;
    display: flex;
    flex-wrap: wrap;

  }

  .presentation {
    border: 2px solid red;
    flex: 1 1 25%;
    flex-basis: 200px;
    height: inherit;
    display: flex;
    flex-wrap: wrap;
    height: 100vh;
  }

  .presentation > * {
    flex: 1 1 100%;
  }

  .presentation__img {
    border: 2px solid skyblue;
    flex-grow: 1;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .presentation__img figure {
    border: 2px solid blue;
    display:flex;
    justify-content: center;
  }
  .presentation__img img {
    border-radius: 50%;
  }

  .presentation__info {
    border: 2px solid green;
    flex-grow: 5;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    text-align: center;
    
  }

  
  

  /* nav */
  .menu__list {
    list-style: none;
    padding: 0;
  }
  /* /nav */

  /* social */
  .presentation__info_social {
    display: flex;
  }
  /* /social */

  /* layout */
  .layout {
    border: 2px solid yellow;
    flex: 4 1 75%;
    flex-basis: 400px;
    height: inherit;
    overflow-y: scroll;
  }

  .layout__works {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    /* justify-content: center; */
    
    
  }

  .layout__works_item {
    /* border: 2px solid black; */
    /* flex: 1 1 50%; */
  }

  .layout_works_item_description {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  /* certificados */
  .layout__certs {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
  }
  /* /certificados */

  /* conocimientos */
  .layout__knowledge {
    border: 3px solid black;
    /* max-width: 750px; */
    margin: 0 auto;
    display: flex;
    align-items: start;
    /* justify-content: space-around; */
  }

  .layout__knowledge_col {
    border: 2px solid green;
    margin: 20px;
    padding: 20px;
    text-align: center;
    flex: 1;
    display: flex;
    flex-wrap: wrap;
  }

  .layout__knowledge_col_features {
    list-style: none;
    padding: 0;
  }

  .layout__knowledge_col_features:last-child {
    border-bottom: 0;
  }

  .layout__knowledge_col > * {
    flex: 1 1 100%;
  }

  /* /conocimientos */

  /* Info y contacto */
  .layout__info {
    display: flex;
  }

  

  .layout__info__bio {
    flex: 1;
    display:flex;
    /* flex-direction: column; */
    flex-wrap: wrap;
    justify-content: center;
    align-content: center;
    border: 3px solid black;
  }
  .layout__info__bio_studies {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .layout__info__contact {
    flex: 1;
    border: 3px solid black;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }

  /* /Info y contacto */


  /* /layout */


</style>

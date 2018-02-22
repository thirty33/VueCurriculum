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
          <p>Joel Gustavo Suarez Rodriguez.<br> Desarrollador web Frontent. <br>
            Santiago de Cali.
          </p>
        </div>
        <!-- menu -->
        <div class="presentation__info_nav">
          <nav class="menu" id="menu">
            <ul class="menu__list">
              <li><a href="#works">Trabajos</a></li>
              <li><a href="#certs">Certificaciones</a></li>
              <li><a href="#knowledge" target="">Conocimientos</a></li>
              <li><a href="#info" target="">Bio y Contacto</a></li>
            </ul>
          </nav>
        </div>
        <!-- /menu -->
        
        <!-- social media -->
        <div class="presentation__info_social">
          <div class="item item1">
            <figure class="logo">
              <a href="https://github.com/thirty33" target="_blank">
                <img src="../static/github.png" width="25" />
              </a>
            </figure>
          </div>
          <div class="item item2">
            <figure class="logo">
              <a href="https://www.linkedin.com/in/joel-gustavo-suarez-rodriguez-1a4569156/" target="_blank">
                <img src="../static/linkedin.png" width="25" />
              </a>
            </figure>
          </div>
          <div class="item item3">
            <figure class="logo">
              <a href="https://twitter.com/HiramArch" target="_blank">
                <img src="../static/twitter.png" width="25" />
              </a>
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
      <section id="works" class="layout__works">
        <article class="layout__works_item">
          <div class="layout_works_item_img">
            <figure>
              <a href="http://jetsetmobile.info" target="_blank">
                <img src="../static/jetsetmobile.png" width="250" />
              </a>
            </figure>
          </div>
          <div class="layout_works_item_description">
            <aside class="layout_works_item_description_aside">
              <h7>Tecnologias: Vuejs, Firebase</h7><br>
              <h7>Url: jetsetmobile.info</h7><br>
              <h7><a href="https://github.com/thirty33/Vuejs-Firebase" target="_blank">Github</a></h7>
            </aside>
          </div>
        </article>
        <article class="layout__works_item">
          <div class="layout_works_item_img">
            <figure>
              <a href="https://github.com/thirty33/MeetupsApp" target="_blank">
                <img src="../static/meetupsapp.png" width="250" />
              </a>
            </figure>
          </div>
          <div class="layout_works_item_description">
            <aside class="layout_works_item_description_aside">
              <h7>Tecnologias: Vuejs, Firebase</h7><br>
              <h7>Url:</h7><br>
              <h7><a href="https://github.com/thirty33/MeetupsApp" target="_blank">Github</a></h7>
            </aside>
          </div>
        </article>
        <article class="layout__works_item">
          <div class="layout_works_item_img">
            <figure>
              <a href="https://github.com/thirty33/LearningBootstrap" target="_blank">
                <img src="../static/exampleshop.png" width="250" />
              </a>
            </figure>
          </div>
          <div class="layout_works_item_description">
            <aside class="layout_works_item_description_aside">
              <h7>Tecnologias: Bootstrap, Jquery</h7><br>
              <h7>Url: jetsetmobile.info</h7><br>
              <h7><a href="https://github.com/thirty33/LearningBootstrap" target="_blank">Github</a></h7>
            </aside>
          </div>
        </article>
        <article class="layout__works_item">
          <div class="layout_works_item_img">
            <figure>
              <a href="https://github.com/thirty33/FoundationProject" target="_blank">
                <img src="../static/rockatpark.png" width="250" />
              </a>
            </figure>
          </div>
          <div class="layout_works_item_description">
            <aside class="layout_works_item_description_aside">
              <h7>Tecnologias: Foundation</h7><br>
              <h7>Url: jetsetmobile.info</h7><br>
              <h7><a href="https://github.com/thirty33/FoundationProject" target="_blank">Github</a></h7>
            </aside>
          </div>
        </article>
        <article class="layout__works_item">
          <div class="layout_works_item_img">
            <figure>
              <a href="https://github.com/thirty33/Invie" target="_blank">
                <img src="../static/invie.png" width="250" />
              </a>
            </figure>
          </div>
          <div class="layout_works_item_description">
            <aside class="layout_works_item_description_aside">
              <h7>Tecnologias: HTML5, CSS3</h7><br>
              <h7>Url: jetsetmobile.info</h7><br>
              <h7><a href="https://github.com/thirty33/Invie" target="_blank">Github</a></h7>
            </aside>
          </div>
        </article>
      </section>
      <!-- /works -->
      <div class="layout__title">
        <h2>Certificados</h2>
      </div>
      <!-- certificados -->
      <div id="certs" class="layout__certs">
        <article class="layout__certs_item">
          <div class="layout__certs_item_img">
            <figure>
            <a href="https://platzi.com/@HiramBridge/curso/fundamentos-javascript/diploma/" target="_blank">
              <img src="../static/javascript.png" width="250" />
            </a>  
            </figure>
          </div>
        </article>
        <article class="layout__certs_item">
            <div class="layout__certs_item_img">
              <figure>
                <a href="https://platzi.com/@HiramBridge/curso/vuejs/diploma/" target="_blank">
                  <img src="../static/postcss.png" width="250" />
                </a>  
              </figure>
            </div>
        </article>
        <article class="layout__certs_item">
          <div class="layout__certs_item_img">
            <figure>
              <a href="https://platzi.com/@HiramBridge/curso/responsive-design/diploma/" target="_blank">
                <img src="../static/responsive.png" width="250" />
              </a>  
            </figure>
          </div>
          
        </article>
        <article class="layout__certs_item">
          <div class="layout__certs_item_img">
            <figure>
              <a href="https://platzi.com/@HiramBridge/curso/vuejs/diploma/" target="_blank">
                <img src="../static/vue.png" width="250" />
              </a>  
            </figure>
          </div>
          
        </article>
        <article class="layout__certs_item">
          <div class="layout__certs_item_img">
            <figure>
              <a href="https://platzi.com/@HiramBridge/curso/git-github-2016/diploma/" target="_blank">
                <img src="../static/git.png" width="250" />
              </a>  
            </figure>
          </div>
          
        </article>
        <article class="layout__certs_item">
          <div class="layout__certs_item_img">
            <figure>
              <a href="https://platzi.com/@HiramBridge/curso/html5-css3/diploma/" target="_blank">
                <img src="../static/desarrollo.png" width="250" />
              </a>  
            </figure>
          </div>
          
        </article>
        <article class="layout__certs_item">
          <div class="layout__certs_item_img">
            <figure>
              <a href="https://platzi.com/@HiramBridge/curso/postcss-2016/diploma/" target="_blank">
                <img src="../static/postcss.png" width="250" />
              </a>  
            </figure>
          </div>
          
        </article>
        <article class="layout__certs_item">
          <div class="layout__certs_item_img">
            <figure>
              <a href="https://platzi.com/@HiramBridge/curso/fw-frontend/diploma/" target="_blank">
                <img src="../static/frameworks.png" width="250" />
              </a>  
            </figure>
          </div>
          
        </article>
      </div>
      <!-- /certificados -->

      <!-- conocimientos -->
      <div class="layout__title">
        <h2>Conocimientos</h2>
      </div>
      <div id="knowledge" class="layout__knowledge">
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
        <h2>Bio y contacto</h2>
      </div>
      <div id="info" class="layout__info">
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
              Ingenieria de Sistemas en ULA Venezuela (5to Semestre)
              Estudiante activo en Platzi.com
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
    color: white;
    background-color: #EDEDED;
  }

  #App {
    height:100vh;
    display: flex;
    flex-wrap: wrap;
  }

  .presentation {
    flex: 1 1 25%;
    flex-basis: 200px;
    height: inherit;
    display: flex;
    flex-wrap: wrap;
    height: 100vh;
    background-color: #13507D;
  }

  .presentation > * {
    flex: 1 1 100%;
  }

  .presentation__img {
    flex-grow: 1;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .presentation__img figure {
    display:flex;
    justify-content: center;
    
  }
  .presentation__img img {
    border-radius: 50%;
  }

  .presentation__info {
    /* border: 2px solid green; */
    flex-grow: 5;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    text-align: center;
    background-color: #C4C4C4;
    margin: 10px 30px;
    border-radius: 5%;
  }

  .presentation__info_text {
    background-color: #EDE6E6;
    margin-top: 15px;
    padding: 0 10px;
    border-radius: 3%;
  }

  
  

  /* nav */
  .menu__list {
    padding: 0;
    list-style: none; 
  }

  .menu__list li {
    margin-top: 5px;
  }
  .menu__list li a {
    text-decoration: none;
    color: white;
    padding: 3px 2px;
  }

  .menu__list li a:hover {
    background-color: #635858;
  }  
  /* /nav */

  /* social */
  .presentation__info_social {
    display: flex;
  }
  /* /social */

  /* layout */

  .layout__title {
    background-color: #A7C4D9;
    margin: 0 15px;
    border-radius: 1%;
  }

  .layout__title h2 {
    padding: 2px 2px 0 2px;
  }

  .layout {
    flex: 4 1 75%;
    flex-basis: 400px;
    height: inherit;
    overflow-y: scroll;
  }

  .layout__works {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
  }

  .layout__works_item {
    margin-bottom: 15px;
  }

  .layout__works_item  figure {
    margin: 0 35px; 
  }

  .layout_works_item_description {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #C4C4C4;
    margin: 0 35px;
    border-radius: 3px; 
  }

  layout_works_item_description_aside {
    display: flex;
    flex-direction: column;
    text-align: center;
  }

  .layout_works_item_description_aside a {
    color: white;
    text-decoration: none;
  }

  /* certificados */
  .layout__certs {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
  }

  .layout__certs_item {
    background-color:  #C4C4C4;
    /* margin-bottom: 15px; */
    margin: 5px 22px;
    border-radius: 2%;  
  }

  .layout__certs_item figure {
    margin: 10px 10px 10px 10px;
    /* padding: 5px 5px;  */
    display: flex;
    justify-content: center;
  }
  /* /certificados */

  /* conocimientos */
  .layout__knowledge {
    margin: 0 auto;
    display: flex;
    text-align: center;
    align-items: stretch;
  }

  .layout__knowledge_col {
    margin: 20px;
    padding: 20px;
    /* text-align: center; */
    flex: 1;
    display: flex;
    flex-wrap: wrap;
    background-color: #C4C4C4;
    text-align: center;
    border-radius: 5%;
  }

  .layout__knowledge_col > * {
    flex: 1 1 100%;
  }

  .layout__knowledge_col_features {
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 0;
    margin-top: 0;
  }

  .layout__knowledge_col_features li {
    text-align: inherit;
    margin-top: 5px;
    list-style: none;
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
    display: grid;
    grid-gap: 15px;
    margin: 0 15px;
    grid-template-columns: repeat(2, 1fr) 
    
  }

  .layout__info__bio {
    flex: 1;
    display:flex;
    flex-wrap: wrap;
    justify-content: flex-start;
    align-content: center;
    border-radius: 1%;
    background: #DB8F8F;
  }

  .layout__info__bio h4,
  .layout__info__bio p {
    margin: 5px 15px;
  }

  .layout__info__bio_studies {
    display: flex;
    flex-direction: column;
  }

  .layout__info__contact {
    flex: 1;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    background: #DB8F8F;
    border-radius: 1%;
  }

  .layout__info__contact h4 {
    margin: 5px 0;
  }

  /* /Info y contacto */


  /* /layout */


</style>

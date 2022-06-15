<script setup></script>

<template>
    <header>
      <nav class="navbar btn">
  <div class="container-fluid">
   <router-link to="/about"> 
     <a class="navbar">
      <img class="logo" src="/images/Captura_de_tela_de_2022-06-11_08-50-51.png" alt="" width="20" height="30">
      IFC dogs
    </a>
    </router-link>
    <div class="botao1"><button id="botao" class="btn btn"><router-link style="text-decoration: none;" to="/about">abaut</router-link></button></div>
    <div class="botao1"><button id="botao" class="btn btn"><router-link style="text-decoration: none;" to="/about">abaut</router-link></button></div>
    <div class="botao1"><button id="botao" class="btn btn"><router-link style="text-decoration: none;" to="/about">abaut</router-link></button></div>
    <div class="botao1"><button id="botao" class="btn btn"><router-link style="text-decoration: none;" to="/about">abaut</router-link></button></div>
  </div>
</nav>
    </header>
    <main>
    <div id="carrocel" calss="justify-content-center">  
      <section class="carousel" aria-label="Gallery">
  <ol class="carousel__viewport">
    <li id="carousel__slide1"
        tabindex="0"
        class="carousel__slide">
      <div class="carousel__snapper">
        <a href="#carousel__slide4"
           class="carousel__prev">Go to last slide</a>
        <a href="#carousel__slide2"
           class="carousel__next">Go to next slide</a>
      </div>
    </li>
    <li id="carousel__slide2"
        tabindex="0"
        class="carousel__slide">
      <div class="carousel__snapper"></div>
      <a href="#carousel__slide1"
         class="carousel__prev">Go to previous slide</a>
      <a href="#carousel__slide3"
         class="carousel__next">Go to next slide</a>
    </li>
    <li id="carousel__slide3"
        tabindex="0"
        class="carousel__slide">
      <div class="carousel__snapper"></div>
      <a href="#carousel__slide2"
         class="carousel__prev">Go to previous slide</a>
      <a href="#carousel__slide4"
         class="carousel__next">Go to next slide</a>
    </li>
    <li id="carousel__slide4"
        tabindex="0"
        class="carousel__slide">
      <div class="carousel__snapper"></div>
      <a href="#carousel__slide3"
         class="carousel__prev">Go to previous slide</a>
      <a href="#carousel__slide1"
         class="carousel__next">Go to first slide</a>
    </li>
  </ol>
  <aside class="carousel__navigation">
    <ol class="carousel__navigation-list">
      <li class="carousel__navigation-item">
        <a href="#carousel__slide1"
           class="carousel__navigation-button">Go to slide 1</a>
      </li>
      <li class="carousel__navigation-item">
        <a href="#carousel__slide2"
           class="carousel__navigation-button">Go to slide 2</a>
      </li>
      <li class="carousel__navigation-item">
        <a href="#carousel__slide3"
           class="carousel__navigation-button">Go to slide 3</a>
      </li>
      <li class="carousel__navigation-item">
        <a href="#carousel__slide4"
           class="carousel__navigation-button">Go to slide 4</a>
      </li>
    </ol>
  </aside>
</section>
    </div>
      <div class="dogslinks"> 
        <div>
          <router-link style="text-decoration: none;  margin: 1% 10%;" to="/about">fumaça</router-link>
          <router-link style="text-decoration: none;  margin: 1% 10%;" to="/about">maicon</router-link>
          <router-link style="text-decoration: none;  margin: 1% 10%;" to="/about">formiga</router-link>
          <router-link style="text-decoration: none;  margin: 1% 10%;" to="/about">churras</router-link>
        </div>
      </div>
    <div class="subtitulo">
        <h4>Novidades</h4>
    </div>
  <div class="grid">
    <div class="conteudolados">conteudo1</div>
    <div class="conteudo1">conteudo2</div>
    <div class="conteudolados">conteudo2</div>

  </div>  
      <br/>
      <div class="subtitulo">
        <h4>Comunidade</h4>
    </div>
    <div id="fundo-if">
      <div class="ifc">
      <img class="img-if" src="/src/assets/images/Captura_de_tela_de_2022-06-11_08-50-51.png" alt="">
      <button class="btn btn" style="margin:0 40% 1%; align-content:center;border-color: rgb(37, 133, 58);"><a href="https://araquari.ifc.edu.br">conheca o ifc</a></button>
      </div>
      
    </div>
    </main>
      <footer class="d-flex flex-wrap justify-content-between align-items-center py-3 my-4">
    <div class="col-md-4 d-flex align-items-center">
      <a href="/" class="mb-3 me-2 mb-md-0 text-muted text-decoration-none lh-1">
        <svg class="bi" width="30" height="24"><use xlink:href="#bootstrap"></use></svg>
      </a>
      <span class="mb-3 mb-md-0 text-muted">© 2022 Company, Inc</span>
    </div>

    <ul class="nav col-md-4  list-unstyled d-flex">
      <li class="ms-3"><a class="text-muted" href="#">(047) 99999-9999<svg class="bi" width="24" height="24"><use xlink:href="#twitter">oi</use></svg></a></li>
      <li class="ms-3"><a class="text-muted" href="#">hakctouille<svg class="bi" width="24" height="24"><use xlink:href="#instagram"></use></svg></a></li>
      <li class="ms-3"><a class="text-muted" href="#">@hacktouille<svg class="bi" width="24" height="24"><use xlink:href="#facebook"></use></svg></a></li>
    </ul>
      </footer>
</template>

<style>
.ifc{
  background-color: rgb(255, 255, 255);
  max-width: 45%;
  margin-left: 2rem;
  border-radius: 1rem;
}
.img-if{
  align-content: flex-start;
  margin: 1rem 1rem;
  width: 80%;
  height: 20%;
  border-radius: 1rem;
}
#fundo-if{
  background-color: rgb(68, 0, 255);
  padding: 1rem 0;
  text-align: start;
  margin:2rem 0;
  height: 15rem;
}
.grid{
  display: grid;
  grid-template-columns:repeat(3, 33%);
  margin: 4rem 10%;
  align-content: center;
}
.conteudolados {border: 2px solid rgb(37, 133, 58);
            margin: 3rem 2rem 1rem 2rem;
            height: 10rem;
            ;}
.conteudo1{
  border: 2px solid rgb(37, 133, 58);
  margin: 1rem 2rem 3rem 2rem;
  height: 10rem;
}
#news{
  background-color: rgb(37, 133, 58);
}
#novidades{
  background-color: rgb(37, 133, 58);
  text-align: center;
  padding: 2rem 1rem;
  margin: 10% 4rem;
  align-content: center;
}
.subtitulo{
  background-color: rgb(37, 133, 58);
  padding: 1rem 0;
  border-radius:1em;
  text-align: center;
}
body {
  background-image: linear-gradient( #ffffff 0%, #dff4df 100%);
}
nav{
  background-color: #b3c9b2;
  margin: 0 0;
}
.container-fluid{
  max-width: 70%;
}
.dogslinks{
  background-color: rgb(37, 133, 58);
  margin: 8% 15%;
  padding: 1% 0;
  border-radius:1em;
}
#botao{
  background-color: rgb(37, 133, 58);
}
p{ 
  text-decoration-color: #962525;
}
#carrocel{
  margin:2rem;
}
@keyframes tonext {
  75% {
    left: 0;
  }
  95% {
    left: 100%;
  }
  98% {
    left: 100%;
  }
  99% {
    left: 0;
  }
}

@keyframes tostart {
  75% {
    left: 0;
  }
  95% {
    left: -300%;
  }
  98% {
    left: -300%;
  }
  99% {
    left: 0;
  }
}

@keyframes snap {
  96% {
    scroll-snap-align: center;
  }
  97% {
    scroll-snap-align: none;
  }
  99% {
    scroll-snap-align: none;
  }
  100% {
    scroll-snap-align: center;
  }
}



* {
  box-sizing: border-box;
  scrollbar-color: transparent transparent; /* thumb and track color */
  scrollbar-width: 0px;
}

*::-webkit-scrollbar {
  width: 0;
}

*::-webkit-scrollbar-track {
  background: transparent;
}

*::-webkit-scrollbar-thumb {
  background: transparent;
  border: none;
}

* {
  -ms-overflow-style: none;
}

ol, li {
  list-style: none;
  margin: 0;
  padding: 0;
}

.carousel {
  position: relative;
  padding-top: 30%;
  filter: drop-shadow(0 0 10px #0003);
  perspective: 100px;
}

.carousel__viewport {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  display: flex;
  overflow-x: scroll;
  counter-reset: item;
  scroll-behavior: smooth;
  scroll-snap-type: x mandatory;
}

.carousel__slide {
  position: relative;
  flex: 0 0 100%;
  width: 100%;
  background-color: #f99;
  counter-increment: item;
}

.carousel__slide:nth-child(even) {
  background-color: #99f;
}

.carousel__slide:before {
  content: counter(item);
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate3d(-50%,-40%,70px);
  color: #fff;
  font-size: 2em;
}

.carousel__snapper {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  scroll-snap-align: center;
}

@media (hover: hover) {
  .carousel__snapper {
    animation-name: tonext, snap;
    animation-timing-function: ease;
    animation-duration: 4s;
    animation-iteration-count: infinite;
  }

  .carousel__slide:last-child .carousel__snapper {
    animation-name: tostart, snap;
  }
}

@media (prefers-reduced-motion: reduce) {
  .carousel__snapper {
    animation-name: none;
  }
}

.carousel:hover .carousel__snapper,
.carousel:focus-within .carousel__snapper {
  animation-name: none;
}

.carousel__navigation {
  position: absolute;
  right: 0;
  bottom: 0;
  left: 0;
  text-align: center;
}

.carousel__navigation-list,
.carousel__navigation-item {
  display: inline-block;
}

.carousel__navigation-button {
  display: inline-block;
  width: 1.5rem;
  height: 1.5rem;
  background-color: rgb(37, 133, 58);
  background-clip: content-box;
  border: 0.25rem solid transparent;
  border-radius: 50%;
  font-size: 0;
  transition: transform 0.1s;
}

.carousel::before,
.carousel::after,
.carousel__prev,
.carousel__next {
  position: absolute;
  top: 0;
  margin-top: 20%;
  width: 4rem;
  height: 4rem;
  transform: translateY(-50%);
  border-radius: 30%;
  font-size: 0;
  outline: 0;
}

.carousel::before,
.carousel__prev {
  left: -1rem;
}

.carousel::after,
.carousel__next {
  right: -1rem;
}

.carousel::before,
.carousel::after {
  content: '';
  z-index: 1;
  background-color: #333;
  background-size: 1.5rem 1.5rem;
  background-repeat: no-repeat;
  background-position: center center;
  color: #fff;
  font-size: 2.5rem;
  line-height: 4rem;
  text-align: center;
  pointer-events: none;
  
}

.carousel::before {
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Cpolygon points='0,50 80,100 80,0' fill='%23fff'/%3E%3C/svg%3E");
}

.carousel::after {
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 100 100' xmlns='http://www.w3.org/2000/svg'%3E%3Cpolygon points='100,50 20,100 20,0' fill='%23fff'/%3E%3C/svg%3E");
}

</style>

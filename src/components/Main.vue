<template>
  <div class="page">
    <div class="section section1">
      <div class="content-container">
        <h1 class="title">More About Damon Vaughn</h1>
        <p class="description">Damon Vaughn is a professor of psychology at the University of Toronto, a clinical psychologist and the author of the multi-million copy bestseller 'The story of my life.'</p>
        <button class="custom-button">Meet The Author</button>
      </div>
     <!------sezzione loghi -->
    </div>
    <div class="section section2">
  <div class="container">
    <div class="image-container">
      <a href="#">
        <img src="/public/ebay-logotan-2x-200x66.png" alt="Immagine 1" />
      </a>
    </div>
    <div class="image-container">
      <a href="#">
        <img src="/public/audible-logotan-2x-200x66.png" alt="Immagine 2" />
      </a>
    </div>
    <div class="image-container">
      <a href="#">
        <img src="/public/bb-logotan-2x-200x66.png" alt="Immagine 3" />
      </a>
    </div>
    <div class="image-container">
      <a href="#">
        <img src="/public/kindlefire-logotan-2x-200x66.png" alt="Immagine 4" />
      </a>
    </div>
  </div>
  <!------sezione telefono ------>
    </div>
    <div class="section section3">
      <div class="/public/banner.jpg">
        <div class="container-phone">
      <div class="image-iphone">
        <img src="/public/audible-app-2x.png" alt="Immagine" />
      </div>
      <!-- Contenitore per il testo -->
      <div class="testo-container">
        <h2>New Audiobook</h2>
        <p>NO TIME TO READ? NO PROBLEM.LISTEN TO IT</p>
        <h3>Donec fiingilla nunc eu turpis dignissim, at euismodsapien tincidunt. Maecenas eleifend congue cursus.</h3>
      </div>
    
      <div class="immagini-container">
          <div class="immagine">
            <img src="/public/audible-logo.png" alt="Audible Logo" />
          </div>
          <div class="immagine">
            <img src="/public/bn-logo-tall.png" alt="Barnes & Noble Logo" />
          </div>
          <div class="immagine">
            <img src="/public/kindle-logo-tall.png" alt="Kindle Logo" />
          </div>
        </div>
      </div>
      
      
    </div>
  </div>
  </div>
  
  <div class="section section4">
        <div class="custom-container">
            <h2 class="section-title">Nuova Sezione</h2>
            <p class="section-description">Questa è una nuova sezione con un titolo e una didascalia personalizzati.</p>
          </div>
      </div>
    <div class="section section5">
      
      <div class="content-container">
        <h1 class="Titolo">Upcoming Event</h1>
        <p class="sottotitolo">MEET TEH AUTHOR IN PERSON</p>
        
        <div class="square-container">
          <img src="/public/event-05-400x240.jpg" alt="Immagine 1" class="square-image" />
          <h1 class="Nome">Chicago Book Signing</h1>
          <p class="square-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rerum, dicta consequatur ut enim officiis aspernatur sint voluptas tenetur!1</p>
        </div>
        
        <!-- Contenitore 2 -->
        <div class="square-container">
          <img src="/public/event-04-400x240.jpg" alt="Immagine 2" class="square-image" />
          <h1 class="Nome">Meet & Greet With Amanda</h1>
          <p class="square-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rerum, dicta consequatur ut enim officiis aspernatur sint voluptas tenetur!</p>
        </div>
        
        <!-- Contenitore 3 -->
        <div class="square-container">
          <img src="/public/event-07-400x240.jpg" alt="Immagine 3" class="square-image" />
          <h1 class="Nome">Open Book Dialogues</h1>
          <p class="square-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rerum, dicta consequatur ut enim officiis aspernatur sint voluptas tenetur!</p>
        </div>
      </div>
    </div>
    <div class="section section6">
      <div class="content-container">
        <div class="center-container">
          <h2 class="section-title">Subscribe To My Newsletter</h2>
          <h3 class="section-subtitle">BE NOTTIFICATE ABOUT BOOK SINGING TOUR DATES</h3>
          
          <!-- Barra di Ricerca e Pulsante -->
          <div class="search-bar">
            <input type="text" class="search-input" placeholder="Insert your email..." />
            <button class="search-button">Subscribe</button>
          </div>
        </div>
        
      </div>
    </div>
    <div class="section section7">
      <div class="content-container">
        
      </div>
    </div>
  
</template>

<script>
export default {

}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Caveat:wght@500&family=Fredoka:wght@500&family=Kristi&family=Pacifico&family=Satisfy&display=swap');
.page {
  display: flex;
  flex-direction: column;
  width: 100vw; 
  height: 100vh; 
}

.section {
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
.title {
  color: #F4B429;
font-family: 'Kristi', cursive;
font-size: 80px;
}
.description{
  font-size: 22px;
  text-align: center;
}

.content-container {
  text-align-last: center;
  max-width: 850px; 
  margin: 0 auto
}

.section1 {
  background-color:white; 
}

.custom-button {
  background-color: #49A987;
  color: white;
  border: none;
  border-radius: 5px;
  padding: 10px 20px;
  font-size: 18px;
  cursor: pointer;
  transition: background-color 0.3s ease;
  margin-top: 30px;
  margin-bottom: 100px;
}

.custom-button:hover {
  background-color: #D89E2B;
}
/*sezione loghi */
.section2 {
  background-color: #FEF7E9; 
}

.container{
  display: flex;
  justify-content: space-around; 
 
}

.image-container {
  width: 300px; 
  height: 100px; 
  margin: 1px; 
 
 
}

.image-container img {
  width: 100%;
  height: 60%;
  object-fit:none;
 
}
.section4 {
  background-color: #F0E68C; /* Cambia il colore di sfondo come preferisci */
  color: #333; /* Cambia il colore del testo se necessario */
  text-align: center;
  padding: 100px 0;
}
.custom-container {
  background-color: #fff; 
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); 
  margin-top: 40px;
  margin-right: 200px;
}

.section-title {
  font-size: 36px;
  margin-bottom: 10px;
}

.section-description {
  font-size: 18px;
  color: #777;
}

.section5 {
  background-color: #F4B429; 
  color: #333; 
  text-align: center;
  padding: 100px 0;
}
.section6 {
  background-color: #F0E68C; /* Cambia il colore di sfondo come preferisci */
  color: #333; /* Cambia il colore del testo se necessario */
  text-align: center;
  padding: 50px 0;
}
.section7 {
  background-color: #94f08c; /* Cambia il colore di sfondo come preferisci */
  color: #333; /* Cambia il colore del testo se necessario */
  text-align: center;
  padding: 100px 0;
}










.section3 {
  background-color: #add8e6; 
}
.section3 {
  background-image: url('/public/banner.jpg');  
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  color: white;
  text-align: center; 
  padding: 100px 0; 
  
}

.container-phone {
  display: flex;
  justify-content: center;
  align-items: center;
}

.image-iphone {
  width: 300px;
  height: 347px;
  margin-right: 300px; /* Spazio tra l'immagine e il testo */
}

.image-iphone img {
  width: 439px;
  height: 526px;
  object-fit: cover;
  transform: scale(0.7);
}

.testo-container {
  max-width: 400px; /* Larghezza massima del contenitore del testo */
  text-align: left; /* Allineamento del testo a sinistra */
}

.testo-container h2 {
  font-size: 30px;
  margin-bottom: 10px;
  text-align: center; /* Spazio tra il titolo e il paragrafo */
}
.testo-container p {
  font-size: 15px;
  color:#D89E2B;
  text-align: center;
}
.testo-container h3{
  font-size: 18px;
  text-align: center;
  color:#C5C4C4;
}
.immagini-container {
  display: flex;
  justify-content: space-around;
  margin-top: 20px;

}

.immagine {
  width: 20px;
  height: 20px;
  margin: 0 10px; /* Aggiungi margine tra le immagini */
}

.immagine img {
  width: 300%;
  height: 200%;
  object-fit: cover;
}













/*sezzione 5 */
.section5 {
  background-color: #FEF7E9; /* Cambia il colore di sfondo come preferisci */
  color: #333; /* Cambia il colore del testo se necessario */
  text-align: center;
  padding: 200px 0;
}

/* Stili per i contenitori quadrati */
.square-container {
  width: 260px;
  height: 360px;
  background-color: #fff;
  margin: 10px;
  display: inline-block;
  text-align: center;
}

.square-image {
  width: 100%;
  height: 200px; 
  object-fit: cover;
}

.square-text {
  font-size: 16px;
  margin-top: 10px;}


.Nome {
  font-size: 15px;
}
.sottotitolo {
  color: #F4B429;
}


/*sezione 6 */
.section6 {
  background-image: url('/public/banner-2.jpg'); 
  color: #333;
  text-align: center;
  padding: 30px 0;
  background-repeat: no-repeat;
}

.center-container {
  width: 80%;
  margin: 0 auto;
}

.section-title {
  font-size: 36px;
  margin-bottom: 10px;
  color: white;
}
.section-subtitle {
  font-size: 18px;
  color: #D89E2B;
  margin-bottom: 30px;
}


.search-bar {
  display: flex;
  align-items: center;
  max-width: 300px;
  margin: 0 auto;
}

.search-input {
  flex: 1;
  padding: 10px;
  font-size: 16px;
  border: 1px solid #ccc;
  border-radius: 5px 0 0 5px;
 
}
.search-button {
  background-color: #49A987;
  color: white;
  border: none;
  padding: 10px 20px;
  border-radius:  5px;
  cursor: pointer;
  margin-left: 20px;
}

.search-button:hover {
  background-color: #49A987;
}
</style>

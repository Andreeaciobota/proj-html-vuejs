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
    <div class="section section4">
  <div class="container-left">
    <div class="content">
      <h2>Titolo Sinistro</h2>
      <p>Descrizione sinistra.</p>
    </div>
    <button class="button">Pulsante Sinistro</button>
  </div>
  
  <div class="container-middle">
    <div class="background-box">
      <h2>What The Critics Say</h2>
      <p>TESTIMONIALS FROM AROUND THE WORLD</p>
    </div>
  </div>
  
  <div class="container-right">
    <div class="text-box">
      <p>Testo destro 1.</p>
    </div>
    <div class="text-box">
      <p>Testo destro 2.</p>
    </div>
  </div>
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











.section3 {
  background-color: #add8e6; 
}
.section3 {
  background-image: url('/public/banner.jpg'); /* Percorso dell'immagine di sfondo */
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  color: white; /* Colore del testo */
  text-align: center; /* Allineamento del testo al centro */
  padding: 100px 0; /* Spaziatura interna nella sezione */
  
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

</style>

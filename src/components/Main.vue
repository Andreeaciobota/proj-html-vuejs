<template>
  <div class="page">
    <div class="section section1">
      <div class="content-container">
        <h1 class="title">More About Damon Vaughn</h1>
        <p class="description">Damon Vaughn is a professor of psychology at the University of Toronto, a clinical psychologist and the author of the multi-million copy bestseller 'The story of my life.'</p>
        <button class="custom-button">Meet The Author</button>
      </div>
     
    </div>
    <div class="section section2">
      <h1>seconda sezione</h1>
    </div>
    <div class="section section3">
      <h1>3 sezione</h1>
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

.section2 {
  background-color: #b5e7a0; 
}

.section3 {
  background-color: #add8e6; 
}
</style>

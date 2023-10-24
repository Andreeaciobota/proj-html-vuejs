<template>
  <div>
    <!-- Barra di Navigazione -->
    <nav class="navbar navbar-expand-lg navbar-light custom-navbar-bg">
      <router-link class="navbar-brand" to="/">
        <img src="/public/author-logo-round-200x205.png" alt="Il Tuo Logo" />
      </router-link>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li v-for="item in navItems" :key="item.name" class="nav-item">
            <router-link class="nav-link" :to="item.link">{{ item.name }}</router-link>
          </li>
        </ul>
      </div>
    </nav>

   
    <div class="section">
      <div class="sfondo container">
        
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavbarComponent",
  data() {
    return {
      navItems: [
        { name: "Home", link: "/" },
        { name: "About Me", link: "/about" },
        { name: "Testimonials", link: "/testimonials" },
        { name: "My Blog", link: "/blog" },
        { name: "Meetups", link: "/meetups" },
        { name: "Shop", link: "/shop" },
        { name: "Contact Me", link: "/contact" },
        { name: "Other", link: "/other" }
      ]
    };
  }
};
</script>

<style scoped>

.custom-navbar-bg {
  background-color: transparent;
  width: 100%; 
  margin: 0; 
}

.custom-navbar-bg .nav-link {
  color: black;
}

.section {
  background-image: url('/public/footer-3.jpg');
  background-size: cover; 
  background-position: center; 
  height: 800px; 
}

.sfondo {
  background-size: cover;
  background-position: center;
  padding: 20px;
}
</style>

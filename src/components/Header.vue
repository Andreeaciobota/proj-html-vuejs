<template>
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
  background-color:transparent  
}

.custom-navbar-bg .nav-link {
  color: black; 
}
.section{
  background-image: url('/public/hero-07-2x.jpg');
}
</style>

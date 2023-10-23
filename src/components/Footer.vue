<template>
  <footer class="footer">
    <div class="footer-container">
      <div class="footer-1">
      <div class="footer-item">
        <img src="/public/author-logo-round-small.png" alt="Logo" />
      </div>
    </div>
      <div class="footer-item">
        <h3>About Me</h3>
        <p>Vivamus suscipit tortor eget falias porttitor volupat. nulla quis lorem ut liberomalesuada feugiat.Vivamus suscipit tortor eget falias porttitor volupat. </p>
      </div>
      <div class="footer-1">
        <h3>USEFUL LINKS</h3>
        <ul>
          <li>Latest Book</li>
          <li>Upcoming Articles</li>
          <li>Recent Articles</li>
          <li>Business Enquries</li>
          <li>Visit My Foundation</li>
        </ul>
      </div>
      <div class="footer-1">
        <h3>Contact Info</h3>
        <ul>
          <li>63 E.Studebaker Street Bolingbrook, IL 60440</li>
          <li>Phone: (800)000-0000</li>
          <li>Mobile:(800)000-0000</li>
          <li>Email:info@your-company.com</li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
};
</script>

<style scoped>
.footer {
  background-image: url('/public/footer-3.jpg');
  color: white;
  padding: 20px 0;
}

.footer-container {
  display: flex;
  justify-content: space-around;
 
}

.footer-item {
  text-align:left;
  margin-left: 80px;
  margin-right: 80px;
  margin-top: 100px;
 
}
.footer-1{
  text-align: left;
  margin-left: 60px;
  margin-right: 30px;
  margin-top: 100px;
}

ul {
  list-style: none;
  padding: 0;
}

ul li {
  margin-bottom: 5px;
}
</style>

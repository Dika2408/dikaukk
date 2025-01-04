<template>
  <footer>
    <div class="footer-content">
      <p>&copy; 2025 SMKN 4. All rights reserved.</p>
      <ul class="footer-links">
        <li><a href="#">info@smkn4.sch.id</a></li>
        <li><a href="#">+622265312059</a></li>
        <li><a href="#">--</a></li><i class="bi bi-twitter"></i>
        <li><a href="#">--</a></li>
        <li><a href="#">--</a></li>
      </ul>
    </div>
  </footer>
</template>

<style scoped>
footer {
  background-color: rgba(173, 216, 230, 0.8); /* Light blue with transparency */
  color: #000; /* Black text for contrast */
  padding: 20px 0;
  text-align: center;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.footer-content {
  max-width: 1200px;
  margin: 0 auto;
}

.footer-links {
  list-style: none;
  padding: 0;
  margin: 10px 0 0;
  display: flex;
  justify-content: center;
  gap: 15px;
}

.footer-links li {
  display: inline;
}

.footer-links a {
  color: #000; /* Black text for links */
  text-decoration: none;
  background-color: rgba(255, 255, 255, 0.8); /* Transparent white background */
  padding: 5px 10px;
  border-radius: 5px;
  transition: all 0.3s ease;
}

.footer-links a:hover {
  background-color: rgba(173, 216, 230, 1); /* Solid light blue on hover */
  text-decoration: underline;
}
</style>

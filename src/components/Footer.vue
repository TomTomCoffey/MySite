<script setup lang="ts">
const isMenuActive = false;
</script>

<template>
  <footer class="footer">
    <div class="content has-text-centered">
      <p>
        <span class="footer-name">Thomas Coffey</span>
        <br />
        <span class="footer-email">
          Email:
          <a href="mailto:tomcoffey1017@gmail.com">tomcoffey1017@gmail.com</a> /
          <a href="mailto:coffeyt1@newpaltz.edu">coffeyt1@newpaltz.edu</a>
        </span>
      </p>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  background-color: #3498db;
  color: white;
  padding: 3rem;
  margin-top: 1rem;
}

.footer-name {
  font-size: 1.5rem;
  font-weight: bold;
}

.footer-email a {
  color: white;
  text-decoration: none;
  transition: color 0.3s ease-in-out;
}

.footer-email a:hover {
  color: #ecf0f1;
}
</style>

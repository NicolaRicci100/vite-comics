<script>
export default {
  data() {
    return {}
  }
}
</script>

<template>
  <footer>
    <section class="container">
      <div class="sign">
        <a href="#">sign up now!</a>
      </div>
      <ul>follow us
        <li><img src="../assets/img/footer-periscope.png" alt="Facebook"></li>
        <li><img src="../assets/img/footer-facebook.png" alt="Facebook"></li>
        <li><img src="../assets/img/footer-pinterest.png" alt="Facebook"></li>
        <li><img src="../assets/img/footer-youtube.png" alt="Facebook"></li>
        <li><img src="../assets/img/footer-twitter.png" alt="Facebook"></li>
      </ul>
    </section>
  </footer>
</template>

<style scoped>
footer {
  height: 100px;
  background-color: black;
  color: deepskyblue;
}

.sign {
  border: 2px solid blue;
  padding: 10px;
}

a {
  text-decoration: none;
  color: white;
  text-transform: uppercase;
  padding: 10px;
}

section {
  height: 100px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

ul {
  display: flex;
  text-transform: uppercase;
  align-items: center;
  gap: 15px;
}
</style>
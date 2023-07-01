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
        <li><img src="../assets/img/footer-periscope.png" alt="Periscope"></li>
        <li><img src="../assets/img/footer-facebook.png" alt="Facebook"></li>
        <li><img src="../assets/img/footer-pinterest.png" alt="Pinterest"></li>
        <li><img src="../assets/img/footer-youtube.png" alt="Youtube"></li>
        <li><img src="../assets/img/footer-twitter.png" alt="Twitter"></li>
      </ul>
    </section>
  </footer>
</template>

<style lang="scss" scoped>
@use '../assets/scss/colors' as *;

footer {
  height: 100px;
  background-color: $dark;
  color: $blue;
}

.sign {
  border: 2px solid $blue;
  padding: 10px;

  &:hover {
    border: 2px solid white;
    cursor: pointer;

    a {
      color: $blue;
    }
  }
}

a {
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
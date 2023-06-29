<script>
export default {
  data() {
    return {}
  }
}
</script>

<template>
  <section class="first-section">
    <div class="container content">
      <p>&rarr; Content goes here &larr;</p>
    </div>
  </section>
  <section class="second-section">
    <ul class="container navbar">
      <li>
        <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital Comics">
        <p>digital comics</p>
      </li>
      <li>
        <img src="../assets/img/buy-comics-merchandise.png" alt="Merchandise">
        <p>dc merchandise</p>
      </li>
      <li>
        <img src="../assets/img/buy-comics-subscriptions.png" alt="Subscriptions">
        <p>subscription</p>
      </li>
      <li>
        <img src="../assets/img/buy-comics-shop-locator.png" alt="Shop Locator">
        <p>comic shop locator</p>
      </li>
      <li>
        <img src="../assets/img/buy-dc-power-visa.svg" alt="Power Visa">
        <p>dc power visa</p>
      </li>
    </ul>
  </section>
  <section class="background">
    <div class="container main-footer">
      <div>
        <ul><strong>DC COMICS</strong>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
        </ul>
        <ul><strong>SHOP</strong>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
        </ul>
      </div>
      <ul><strong>DC</strong>
        <li>Terms of Use</li>
        <li>Privacy policy (New)</li>
        <li>Ad Choices</li>
        <li>Advertising</li>
        <li>Jobs</li>
        <li>Subscriptions</li>
        <li>Talent Workshops</li>
        <li>CPSC Certificates</li>
        <li>Ratings</li>
        <li>Shop help</li>
        <li>Contact Us</li>
      </ul>
      <ul><strong>SITES</strong>
        <li>DC</li>
        <li>MAD Magazine</li>
        <li>DC Kids</li>
        <li>DC Universe</li>
        <li>DC Power Vista</li>
      </ul>
    </div>
  </section>
</template>

<style scoped>
section {
  min-height: 100px;
}

.content {
  height: 120px;
  display: flex;
  align-items: center;
  font-size: 30px;
}

.navbar {
  height: 120px;
  display: flex;
  align-items: center;
  font-size: 15px;
}

.first-section {
  background-color: black;
  color: white;
  font-weight: 700;
  font-size: 25px;
}

.second-section {
  background-color: cornflowerblue;
  color: white;
  text-transform: uppercase;
}

.navbar {
  justify-content: space-evenly;
}

.navbar img {
  height: 50px;
  padding: 10px;
}

.background {
  background-image: url(../assets/img/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: 100%;
}

.main-footer {
  display: flex;
  gap: 20px;
  color: white;
  min-height: 50vh;
  padding-top: 50px;
}

.main-footer ul {
  margin: 15px;
}

.main-footer ul li {
  font-size: 12px;
  font-weight: 300;
  padding: 2px 0;
  color: gainsboro;
}

ul li {
  display: flex;
  align-items: center;
}
</style>
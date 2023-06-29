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
  <section>
    <div class="container main-footer">
      <ul>dc comics
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
      </ul>
      <ul>shop
        <li>lorem</li>
        <li>lorem</li>
      </ul>
      <ul>dc
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
      </ul>
      <ul>sites
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
        <li>lorem</li>
      </ul>
    </div>
  </section>
</template>

<style scoped>
section {
  min-height: 100px;
}

.content {
  height: 100px;
  display: flex;
  align-items: center;
  font-size: 30px;
}

.navbar {
  height: 100px;
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

.main-footer {
  display: flex;
}

ul li {
  display: flex;
  align-items: center;
}
</style>
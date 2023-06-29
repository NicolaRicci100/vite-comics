<script>
export default {
  data() {
    return {}
  }
}
</script>

<template>
  <section>
    <div class="container content">
      <p>Content goes here</p>
    </div>
  </section>
  <section>
    <ul class="container navbar">
      <li>digital comics</li>
      <li>dc merchandise</li>
      <li>subscription</li>
      <li>comic shop locator</li>
      <li>dc power visa</li>
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
  background-color: gainsboro;
  min-height: 100px;
}

.content,
.navbar {
  height: 100px;
  display: flex;
  align-items: center;
}

.navbar {
  justify-content: center;
}

.main-footer {
  display: flex;
}
</style>
<script>
export default {
  data() {
    return {
      links: [
        {
          text: 'Characters',
          url: '#',
          current: false,
        },
        {
          text: 'Comics',
          url: '#',
          current: true,
        },
        {
          text: 'Movies',
          url: '#',
          current: false,
        },
        {
          text: 'TV',
          url: '#',
          current: false,
        },
        {
          text: 'Games',
          url: '#',
          current: false,
        },
        {
          text: 'Collectibles',
          url: '#',
          current: false,
        },
        {
          text: 'Videos',
          url: '#',
          current: false,
        },
        {
          text: 'Fans',
          url: '#',
          current: false,
        },
        {
          text: 'News',
          url: '#',
          current: false,
        },
        {
          text: 'Shop',
          url: '#',
          current: false,
        }
      ]
    }
  }
}
</script>

<template>
  <header>
    <nav class="container">
      <figure>
        <img src="../assets/img/dc-logo.png" alt="Logo DC">
      </figure>
      <ul>
        <li v-for="link in links" :key="link.text">{{ link.text }}</li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
header {
  height: 110px;
}

nav {
  height: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

ul {
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: 700;
  text-transform: uppercase;
  color: gray;
  gap: 15px;
}

ul li:hover {
  color: deepskyblue;
  cursor: pointer;
}

img {
  width: 70%;
}
</style>
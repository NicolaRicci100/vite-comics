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
        <li v-for="link in links" :key="link.text">
          <a :class="{ active: link.current }" :href="link.url">{{ link.text }}</a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style lang="scss" scoped>
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

  li a.active,
  li a:hover {
    color: rgb(0, 130, 249);
    cursor: pointer;
  }
}

img {
  width: 70%;
}
</style>
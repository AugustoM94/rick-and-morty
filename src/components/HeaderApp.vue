<template>
  <header class="bg-white p-3">
    <div class="row d-flex justify-content-space-around align-items-center">
      <div class="col-4">
        <img src="/vue-dc-comics-1/img/dc-logo.png" alt="logo-dc">
      </div>
      <div class="col-8">
        <ul class="d-flex margin-check">
          <li
            class="px-3"
            v-for="(link, index) in links"
            :key="index"
            :class="{ 'active': index === activeIndex }"
            @click="setActive(index)"
          >
            <a href="#">{{ link.text }}</a>
          </li>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      links: [
        { text: "Characters" },
        { text: "Comics" },
        { text: "Movies" },
        { text: "TV" },
        { text: "Collectibles" },
        { text: "Videos" },
        { text: "Fans" },
        { text: "News" },
        { text: "Shop" },
      ],
      activeIndex: null,
    };
  },
  methods: {
    setActive(index) {
      this.activeIndex = index;
    },
  },
};
</script>

<style lang="css" scoped>
li {
  list-style: none;
}

a {
  text-decoration: none;
  color: black;
  font-weight: 500;
  font-weight: bolder;
  text-transform: uppercase;
  font-size: 0.7rem;
}

a:hover {
  color: #0282f9;
}

img {
  width: 70px;
}

.active {
  border-bottom: 2px solid blue;
}
</style>

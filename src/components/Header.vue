<template>
  <header class="container">
      <a href="#">
          <img src="../assets/images/dc-logo.png" alt="DC Logo">
      </a>
      <nav>
          <ul>
              <li v-for="(link, index) in links" :key="index">
                  <a :class="{active: link.active}" :href="link.url">{{link.text}}</a>
              </li>
          </ul>
      </nav>
  </header>
</template>

<script>
export default {
    name: "Header",
    data() {
        return {
            links: [
                {
                    text: "CHARACTERS",
                    url: "/characters",
                    active: false
                },
                {
                    text: "COMICS",
                    url: "/comics",
                    active: true
                },
                {
                    text: "MOVIES",
                    url: "/movies",
                    active: false
                },
                {
                    text: "TV",
                    url: "/tv",
                    active: false
                },
                {
                    text: "GAMES",
                    url: "/games",
                    active: false
                },
                {
                    text: "COLLECTIBLES",
                    url: "/collectibles",
                    active: false
                },
                {
                    text: "VIDEOS",
                    url: "/videos",
                    active: false
                },
                {
                    text: "FANS",
                    url: "/fans",
                    active: false
                },
                {
                    text: "NEWS",
                    url: "/news",
                    active: false
                },
                {
                    text: "SHOP",
                    url: "/shop",
                    active: false
                },
            ]
        }
    }
}
</script>

<style scoped lang="scss">
    @import "../styles/vars";
    header {
        display: flex;
        justify-content: space-between;
        padding: 1rem 0;
        margin-bottom: 2px;
        
        img {
            height: 80px;
        }
    }

    ul {
        display: flex;
        height: 100%;
        align-items: center;
        list-style: none;
        
        a {
        padding-bottom: 3rem;
        margin-right: 30px;
        border-bottom: 4px solid transparent;
        font-size: 12px;
        font-weight: 700;
        &:hover,
        &.active {
            color: $primary-color;
            border-bottom-color: $primary-color;
        }
        }
    }
</style>
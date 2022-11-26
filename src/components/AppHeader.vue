<script>
export default {
  name: "AppHeader",
  data() {
    return {
      links: [
        {
          href: "#",
          label: "CHARACTERS",
          active: false,
        },
        {
          href: "#",
          label: "COMICS",
          active: true,
        },
        {
          href: "#",
          label: "MOVIES",
          active: false,
        },
        {
          href: "#",
          label: "TV",
          active: false,
        },
        {
          href: "#",
          label: "GAMES",
          active: false,
        },
        {
          href: "#",
          label: "COLLECTIBLUES",
          active: false,
        },
        {
          href: "#",
          label: "VIDEOS",
          active: false,
        },
        {
          href: "#",
          label: "FANS",
          active: false,
        },
        {
          href: "#",
          label: "NEWS",
          active: false,
        },
        {
          href: "#",
          label: "SHOP",
          active: false,
        },
      ],
    };
  },
  methods: {
    changeLink(index) {
      console.log(index);
      this.links.forEach((elm, i) => {
        if (i === index) {
          elm.active = true;
        } else {
          elm.active = false;
        }
      });
    },
  },
};
</script>

<template>
  <header class="container">
    <div class="logo">
      <img src="../assets/dc-logo.png" alt="Logo-header" />
    </div>
    <nav class="main-nav">
      <ul>
        <li v-for="(item, index) in links">
          <a
            :href="item.href"
            :class="{ active: item.active }"
            @click.prevent="changeLink(index)"
          >
            {{ item.label }}
          </a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style lang="scss" scoped>
header {
  display: flex;
  justify-content: space-between;
  .main-nav {
    display: flex;
    align-items: center;
  }
}
ul {
  display: flex;
  height: 100%;
  li {
    display: flex;
    align-items: center;
    padding: 0 10px;
    list-style: none;
  }
}

li a {
  display: flex;
  align-items: center;
  height: 100%;
  text-decoration: none;
  color: #000;
  font-size: 13px;
  font-weight: bold;
}

.active {
  color: var(--primary-color);
  border-bottom: 2px solid var(--primary-color);
}

.logo {
  padding: 10px 0;
  img {
    width: 70px;
  }
}
</style>

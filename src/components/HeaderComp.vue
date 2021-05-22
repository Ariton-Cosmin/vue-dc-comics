<template>
  <header>
    <img src="../assets/img/dc-logo.png" alt="dc-logo" />

    <ul class="text-uppercase">
      <li v-for="(link, index) in links" :key="index">
        <p :class="{ active: link.current }">{{ link.text }}</p>
      </li>
    </ul>
  </header>
</template>

<script>
export default {
  name: "HeaderComp",

  data() {
    return {
      links: [
        {
          text: "characters",
          current: false,
        },
        {
          text: "comics",
          current: true,
        },
        {
          text: "movies",
          current: false,
        },
        {
          text: "tv",
          current: false,
        },
        {
          text: "games",
          current: false,
        },
        {
          text: "collectibles",
          current: false,
        },
        {
          text: "videos",
          current: false,
        },
        {
          text: "fans",
          current: false,
        },
        {
          text: "news",
          current: false,
        },
        {
          text: "shop",
          current: false,
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
header {
  position: relative;
  align-items: center;
  text-align: center;
  width: 100%;
  height: 90px;
  padding: 0 10%;

  img {
    width: 65px;
    position: absolute;
    top: 12px;
    left: 8rem;
  }

  ul {
    display: inline-block;
    li {
      display: inline-block;
      &:first-child {
        margin-left: 480px;
      }

      p {
        margin: 40px 12px;
        padding-bottom: 33px;
        font-size: 11px;
        cursor: pointer;
        &:hover,
        &:active {
          color: rgb(2, 130, 249);
          border-bottom: 4px solid rgb(2, 130, 249);
        }
      }
    }
  }
}
</style>
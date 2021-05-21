<template>
  <header>
    <img src="../assets/img/dc-logo.png" alt="dc-logo" />

    <ul class="text-uppercase">
      <li>characters</li>
      <li class="active">comics</li>
      <li>movies</li>
      <li>tv</li>
      <li>games</li>
      <li>collectibles</li>
      <li>videos</li>
      <li>fans</li>
      <li>news</li>
      <li>shop</li>
    </ul>
  </header>
</template>

<script>
export default {
  name: "HeaderComp",
};
</script>

<style lang="scss" scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  height: 90px;
  padding: 0 10%;

  img {
    width: 65px;
  }

  ul {
    display: inline-block;
    li {
      display: inline-block;
      margin: 0 12px;
      padding: 36px 0;
      font-size: 11px;
      cursor: pointer;
    }

    .active {
      color: rgb(2, 130, 249);
      border-bottom: 4px solid rgb(2, 130, 249);
    }
  }
}
</style>
<template>
  <main>
    <div class="top">
      <h2>
        <span><i class="fas fa-arrow-right"></i></span>
        Content goes here
        <span><i class="fas fa-arrow-left"></i></span>
      </h2>
    </div>

    <div class="bottom">
      <ul>
        <li>
          <img
            src="../assets/img/buy-comics-digital-comics.png"
            alt="buy-comics-digital-comics"
          />
          <p>digital comics</p>
        </li>
        <li>
          <img
            src="../assets/img/buy-comics-merchandise.png"
            alt="buy-comics-merchandise"
          />
          <p>dc merchandise</p>
        </li>
        <li>
          <img
            src="../assets/img/buy-comics-subscriptions.png"
            alt="buy-comics-subscriptions"
          />
          <p>subscription</p>
        </li>
        <li>
          <img
            class="special"
            src="../assets/img/buy-comics-shop-locator.png"
            alt="buy-comics-shop-locator"
          />
          <p>comic shop locator</p>
        </li>
        <li>
          <img
            src="../assets/img/buy-dc-power-visa.svg"
            alt="buy-dc-power-visa"
          />
          <p>dc power visa</p>
        </li>
      </ul>
    </div>
  </main>
</template>

<script>
export default {
  name: "MainComp",
};
</script>

<style lang="scss" scoped>
main {
  display: flex;
  flex-wrap: wrap;
  width: 100%;

  .top {
    width: 100%;
    height: 100px;
    color: white;
    padding: 0 10%;
    line-height: 100px;
    background-color: rgb(28, 28, 28);

    h2 {
      width: 260px;
      cursor: pointer;
    }
  }

  .bottom {
    width: 100%;
    height: 120px;
    padding: 0 10%;
    color: white;
    background-color: rgb(2, 130, 249);

    ul {
      display: flex;
      justify-content: space-between;
      align-items: center;
      width: 100%;
      height: 120px;

      li {
        display: flex;
        align-items: center;
        cursor: pointer;

        img {
          width: 40px;
          margin: 0 1rem;
        }

        p {
          text-transform: uppercase;
          font-size: 12px;
        }

        .special {
          width: 30px;
        }
      }
    }
  }
}
</style>
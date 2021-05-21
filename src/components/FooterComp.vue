<template>
  <footer>
    <div class="top">
      <div class="left">
        <ul>
          <li class="white">dc comics</li>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>
            News
            <ul>
              <li class="white">shop</li>
              <li>Shop DC</li>
              <li>Shop DC Collectibles</li>
            </ul>
          </li>
        </ul>

        <ul>
          <li class="white">dc</li>
          <li>Terms Of Use</li>
          <li>Privacy policy (New)</li>
          <li>Ad Choises</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshops</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>

        <ul>
          <li class="white">sites</li>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>
      </div>

      <div class="right"></div>
    </div>

    <div class="bottom">
      <div class="bottom-right">
        <p class="text-uppercase cursor-pointer">sing-up now!</p>
      </div>
      <div class="bottom-left">
        <ul>
          <li><span class="text-uppercase cursor-pointer">follow us</span></li>
          <li>
            <img
              src="../assets/img/footer-facebook.png"
              alt="footer-facebook"
            />
          </li>
          <li>
            <img src="../assets/img/footer-twitter.png" alt="footer-twitter" />
          </li>
          <li>
            <img src="../assets/img/footer-youtube.png" alt="footer-youtube" />
          </li>
          <li>
            <img
              src="../assets/img/footer-pinterest.png"
              alt="footer-pinterest"
            />
          </li>
          <li>
            <img
              src="../assets/img/footer-periscope.png"
              alt="footer-periscope"
            />
          </li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComp",
};
</script>

<style lang="scss" scoped>
footer {
  width: 100%;

  .top {
    display: flex;
    width: 100%;
    height: 285px;
    padding: 0 10%;
    background-image: url(../assets/img/footer-bg.jpg);

    .left {
      display: flex;
      width: 44%;
      height: 100%;

      ul {
        margin-top: 1.5rem;
        margin-right: 1.5rem;

        .white {
          text-transform: uppercase;
          padding: 5px 0;
          font-size: 13px;
          color: white;
        }

        li {
          list-style: none;
          font-size: 11px;
          line-height: 16px;
          color: gray;
        }
      }
    }
  }

  .right {
    width: 56%;
    height: 100%;
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-size: 400px;
    background-position: center;
  }

  .bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    height: 80px;
    padding: 0 10%;
    background-color: rgb(48, 48, 48);

    p {
      padding: 10px;
      text-align: center;
      color: white;
      border: 1px solid rgb(2, 130, 249);
    }

    ul {
      display: flex;
      justify-content: flex-end;
      align-items: center;

      li {
        list-style: none;
        padding: 0 0.5rem;

        span {
          color: rgb(2, 130, 249);
        }

        img {
          width: 30px;
        }
      }
    }
  }
}
</style>
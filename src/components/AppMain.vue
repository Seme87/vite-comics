<script>
import Sectionproduct from "./Sectionproducts.vue";
import Sectionproducts from "./Sectionproducts.vue";
export default {
  name: "AppMain",
  components: { Sectionproduct },
};
components: {
  Sectionproducts;
}
</script>

<template>
  <main>
    <section class="content"></section>
    <div class="container">
      <Sectionproduct />
    </div>

    <section class="section-card">
      <div class="container">
        <div class="row">
          <div class="card">
            <div class="card-img">
              <img
                src="../assets/buy-comics-digital-comics.png"
                alt="digital comics"
              />
            </div>

            <div class="text">
              <a href="#">DIGITAL COMICS</a>
            </div>
          </div>

          <div class="card">
            <div class="card-img">
              <img
                src="../assets/buy-comics-merchandise.png"
                alt="digital comics"
              />
            </div>

            <div class="text">
              <a href="#">DC MERCHANDAISE</a>
            </div>
          </div>

          <div class="card">
            <div class="card-img">
              <img
                src="../assets/buy-comics-subscriptions.png"
                alt="digital comics"
              />
            </div>

            <div class="text">
              <a href="#">SUBSCRITION</a>
            </div>
          </div>

          <div class="card">
            <div class="card-img">
              <img
                src="../assets/buy-comics-shop-locator.png"
                alt="digital comics"
              />
            </div>

            <div class="text">
              <a href="#">COMICS SHOP LOCATOR</a>
            </div>
          </div>

          <div class="card">
            <div class="card-img">
              <img src="../assets/buy-dc-power-visa.svg" alt="digital comics" />
            </div>

            <div class="text">
              <a href="#">DC POWER VISA</a>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<style lang="scss" scoped>
main {
  background-color: black;
  .content {
    height: 400px;
    background-image: url("../assets/jumbotron.jpg");
    background-repeat: no-repeat;
    background-size: cover;
  }
}

.section-card {
  background-color: var(--primary-color);
  padding: 50px 0px;
}

.row {
  display: flex;
  justify-content: space-between;
  padding: 0 30px;
}

.card {
  display: flex;
}

.card-img {
  height: 50px;
  widows: 40px;
}

.card-img img {
  width: 100%;
  height: 100%;
}

.text a {
  text-decoration: none;
  color: white;
}

.text {
  margin-left: 15px;
  display: flex;
  align-items: center;
}
</style>

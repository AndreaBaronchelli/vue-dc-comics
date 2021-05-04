<template>
  <div class="bar">
      <div class="container">
          <div class="card">
              <img src="../assets/images/buy-comics-digital-comics.png" alt="">
              <h4>DIGITAL COMICS</h4>
          </div>
          <div class="card">
              <img src="../assets/images/buy-comics-merchandise.png" alt="">
              <h4>DC MERCHANDISE</h4>
          </div>
          <div class="card">
              <img src="../assets/images/buy-comics-subscriptions.png" alt="">
              <h4>SUBSCRIPTION</h4>
          </div>
          <div class="card">
              <img src="../assets/images/buy-comics-shop-locator.png" alt="">
              <h4>COMIC SHOP LOCATOR</h4>
          </div>
          <div class="card">
              <img src="../assets/images/buy-dc-power-visa.svg" alt="">
              <h4>DC POWER VISA</h4>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "Bar",
}
</script>

<style scoped>
    .bar {
        
        background-color: #0082f9;
    }

    .container {
        display: flex;
        justify-content: space-between;
        padding: 3rem 1.5rem;
    }

    .card {
        display: flex;
        align-items: center;
        color: #fff;
        cursor: pointer;
    }

    .card img {
        height: 55px;
        margin-right: 10px;
    }

    .card:last-child img {
        height: 35px;
    }
</style>
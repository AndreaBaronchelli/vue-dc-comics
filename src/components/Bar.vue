<template>
  <div class="bar">
      <div class="container">
          <div class="card">
              <img src="../assets/images/buy-comics-digital-comics.png" alt="">
              <div class="label">DIGITAL COMICS</div>
          </div>
          <div class="card">
              <img src="../assets/images/buy-comics-merchandise.png" alt="">
              <div class="label">MERCHANDISE</div>
          </div>
          <div class="card">
              <img src="../assets/images/buy-comics-subscriptions.png" alt="">
              <div class="label">SUBSCRIPTION</div>
          </div>
          <div class="card">
              <img src="../assets/images/buy-comics-shop-locator.png" alt="">
              <div class="label">COMIC SHOP LOCATOR</div>
          </div>
          <div class="card">
              <img src="../assets/images/buy-dc-power-visa.svg" alt="">
              <div class="label">DC POWER VISA</div>
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
        margin-right: 15px;
    }
    .card .label {
        font-size: 14px;
    }

    .card:last-child img {
        height: 35px;
    }
</style>
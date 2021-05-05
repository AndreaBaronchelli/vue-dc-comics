<template>
  <footer>
      <div class="footer-top">
          <div class="container">  
              <div class="col-left">
                  <ul>
                    <li><h3>DC COMICS</h3></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                  </ul>
                  <ul>
                    <li><h3>SHOP</h3></li>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                  </ul>
              </div>
              <ul>
                <li><h3>DC</h3></li>
                <li><a href="#">Terms Of Use</a></li>
                <li><a href="#">Privacy Policy (New)</a></li>
                <li><a href="#">Ad Choices</a></li>
                <li><a href="#">Advertising</a></li>
                <li><a href="#">Jobs</a></li>
                <li><a href="#">Subscriptions</a></li>
                <li><a href="#">Talent Workshops</a></li>
                <li><a href="#">CPSC Certificates</a></li>
                <li><a href="#">Ratings</a></li>
                <li><a href="#">Shop Help</a></li>
                <li><a href="#">Contact Us</a></li>
              </ul>
              <ul>
                <li><h3>SITES</h3></li>
                <li><a href="#">DC</a></li>
                <li><a href="#">MAD Magazine</a></li>
                <li><a href="#">DC Kids</a></li>
                <li><a href="#">DC Universe</a></li>
                <li><a href="#">DC Power Visa</a></li>
              </ul>
              <img src="../assets/images/dc-logo-bg.png" alt="">
          </div>
          
      </div>
      <div class="footer-bottom">
          <div class="container">
              <button>SIGN-UP NOW!</button>
              <div class="social">
                  <ul>
                      <li><h3>FOLLOW US</h3></li>
                      <li><a href="#"><img src="../assets/images/footer-facebook.png" alt=""></a></li>
                      <li><a href="#"><img src="../assets/images/footer-twitter.png" alt=""></a></li>
                      <li><a href="#"><img src="../assets/images/footer-youtube.png" alt=""></a></li>
                      <li><a href="#"><img src="../assets/images/footer-pinterest.png" alt=""></a></li>
                      <li><a href="#"><img src="../assets/images/footer-periscope.png" alt=""></a></li>
                  </ul>
              </div>
          </div>
      </div>
  </footer>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style scoped lang="scss">
    @import "../styles/vars";

    .footer-top {
        height: 380px;
        padding: 2rem 0;
        background-image: url(../assets/images/footer-bg.jpg);
        background-size: cover;
        overflow: hidden;
        
        .container {
            position: relative;
            display: flex;
        }

        ul {
            list-style: none;
            margin-bottom: 25px;
            margin-right: 2rem;
        }

        a {
            margin-bottom: 10px;
            font-size: 12px;
            &:hover {
                color: $primary-color;
            }
        }
        
        h3 {
            color: #fff;
            margin-bottom: 1rem;
        }
        
        img {
            position: absolute;
            right: 0;
            top: -125px;
        }
    }

    .footer-bottom {
        padding: 2rem 0;
        background-color: #303030;
        
        .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        button {
            border: 2px solid $primary-color;
            padding: 1rem;
            font-size: 16px;
            color: #fff;
            background: transparent;
            cursor: pointer;
        }

        .social {
            
            ul {
                display: flex;
                align-items: center;
                list-style: none;
                
                li {
                    margin-right: 20px;
                }

                h3 {
                    color: $primary-color;
                }
            }
        }
    }
</style>
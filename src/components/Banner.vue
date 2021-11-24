<template>
  <section class="vw ">

      <div class="container d-f sp-bw ">
          <!-- left -->
          <div class="hero-left d-f">
              <ul class="li-st ">
                  <h3>DC COMICS</h3>
                  <li>
                      <a href="#">Characters</a>
                  </li>
                  <li>
                      <a href="#">Comics</a>
                  </li>
                  <li>
                      <a href="#">Movies</a>
                  </li>
                  <li>
                      <a href="#">Tv</a>
                  </li>
                  <li>
                      <a href="#">Games</a>
                  </li>
                  <li>
                      <a href="#">Videos</a>
                  </li>
                  <li>
                      <a href="#">News</a>
                  </li>
                  <h3>SHOP</h3>
                  <li>
                      <a href="#">Shop DC</a>
                  </li>
                  <li><a href="#">Shop DC Collectibles</a></li>
              </ul>
              <ul class="li-st ">
                  <h3>DC</h3>
                  <li><a href="#">Term of Use</a></li>
                  <li><a href="#">Privacy policy (new)</a></li>
                  <li><a href="#">Ad Choises</a></li>
                  <li><a href="#">Advertising</a></li>
                  <li><a href="#">Jobs</a></li>
                  <li><a href="#">Subscriptions</a></li>
                  <li><a href="#">Talent Workshopes</a></li>
                  <li><a href="#">CPSCcertificates</a></li>
                  <li><a href="#">Ratings</a></li>
                  <li><a href="#">Shop Help</a></li>
                  <li><a href="#">Contact Use</a></li>

              </ul>
              <ul class="li-st ">
                  <h3>SITES</h3>
                  <li><a href="#">DC</a></li>
                  <li><a href="#">MAD Magazine</a></li>
                  <li><a href="#">DC Kids</a></li>
                  <li><a href="#">DC Universe</a></li>
                  <li><a href="#">DC Power Visa</a></li>
              </ul>

          </div>

          <!-- right -->
          <div class="hero-right">
              <!-- aggiungi immahgine -->
              <img src="'@/assets/dc-logo-bg.png'" alt="">
          </div>
      </div>

  </section>
</template>

<script>
export default {
    name: 'Banner',
}
</script>

<style scoped lang="scss">

section {
    padding-bottom: 30px;
    background-image: url('../assets/footer-bg.jpg');
    background-repeat: round;
}

.hero-left {
    margin-top: 30px;
    font-weight: 900;


    ul{
        margin: 20px;

        h3 {
            margin: 10px 0;
            color: white;
        }
        li {
            
            a {
               font-size: 13px;
               font-weight: 400;
               color: gray;
               text-decoration: none;
             }
        }
    }
        
}



</style>
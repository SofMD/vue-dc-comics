<template>
  <footer>
      <div class="container sp-bw d-f">
          <!-- left -->
          <div>
              <button class="c-pointer">SIGN-UP NOW!</button>
          </div>

          <!-- right -->
          <div class="footer-right d-f al-it-cent ">
              <h3>FOLLOW US</h3>

              <!-- lista icone -->
              <ul class="d-f li-st">
                  <li class="c-pointer">
                      <img src="@/assets/footer-facebook.png" alt="">
                  </li>
                  <li class="c-pointer">
                      <img src="@/assets/footer-twitter.png" alt="">
                  </li>
                  <li class="c-pointer">
                      <img src="@/assets/footer-youtube.png" alt="">
                  </li>
                  <li class="c-pointer">
                      <img src="@/assets/footer-pinterest.png" alt="">
                  </li>
                  <li class="c-pointer">
                      <img src="@/assets/footer-periscope.png" alt="">
                  </li>
                  
              </ul>

          </div>

      </div>

  </footer>
</template>

<script>
export default {
    name: 'Footer',
}
</script>

<style scoped lang="scss">
@import '@/style/variables.scss';

footer {
    background: #333333;
    padding: 30px;

    .container {
        
        button {
            font-size: 1.2rem;
            font-weight: bold;
            color: white;
            background: transparent;
            padding: 12px 12px;
            border: solid 2px $base-blue;
        }

        .footer-right{

            h3 {
                color: $base-blue;
                font-size: 1.3rem;
                font-weight: bold;
                margin-right: 10px;
            }

            li {
                margin-left: 15px;
            }
        }
    }
}

</style>
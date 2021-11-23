<template>
  <section>
      <div class="container d-f sp-bw al-it-cent ">
          <!-- left -->
          <div>
              <img class="head-logo" src="@/assets/dc-logo.png" alt="">
          </div>
          <!-- right -->
          <div>
              <!-- lista -->
              <ul class="d-f li-st t-t-upp ">
                  <li>
                      <a href="#" class="tx-dec">characters</a>
                  </li>
                  <li>
                      <a href="#" class="tx-dec">comics</a>
                  </li>
                  <li>
                      <a href="#" class="tx-dec">movies</a>
                  </li>
                  <li>
                      <a href="#" class="tx-dec">tv</a>
                  </li>
                  <li>
                      <a href="#" class="tx-dec">games</a>
                  </li>
                  <li>
                      <a href="#" class="tx-dec">collectibles</a>
                  </li>
                  <li>
                      <a href="#" class="tx-dec">videos</a>
                  </li>
                  <li>
                      <a href="#" class="tx-dec">fans</a>
                  </li>
                  <li>
                      <a href="#" class="tx-dec">news</a>
                  </li>
                  <li>
                      <a href="#" class="tx-dec">shop</a>
                  </li>
              </ul>
          </div>
      </div>

  </section>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style scoped lang="scss">
@import '@/style/variables.scss';

section {
    background-color: white;
}

.container {
    padding: 20px;

    .head-logo {
    width: 80px;
    margin-left: 10px;
    }
}


ul {
    font-size: 14px;
    font-weight: 500;

    li {
    margin: 0 15px;

        a {
            color: black;

            &:hover {
                color: $base-blue;
            }
        }
    }

}


</style>
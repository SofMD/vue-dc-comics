<template>
  <section>
      <div class="container">
          <!-- left -->
          <div>
              <img class="head-logo" src="@/assets/dc-logo.png" alt="">
          </div>
          <!-- right -->
          <div>
              <!-- lista -->
              <ul>
                  <li>
                      <a href="#">characters</a>
                  </li>
                  <li>
                      <a href="#">comics</a>
                  </li>
                  <li>
                      <a href="#">movies</a>
                  </li>
                  <li>
                      <a href="#">tv</a>
                  </li>
                  <li>
                      <a href="#">games</a>
                  </li>
                  <li>
                      <a href="#">collectibles</a>
                  </li>
                  <li>
                      <a href="#">videos</a>
                  </li>
                  <li>
                      <a href="#">fans</a>
                  </li>
                  <li>
                      <a href="#">news</a>
                  </li>
                  <li>
                      <a href="#">shop</a>
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

section {
    width: 100vw;
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
    font-size: 13px;
    list-style: none;
    text-transform: uppercase;
    font-weight: 500;
    display: flex;

    li {
    margin: 0 15px;

        a {
            color: black;
            text-decoration: none;
        }
    }

}
/* sposta dentro */



</style>
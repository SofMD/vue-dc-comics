<template>
  <section class="vw ">
      <div class="container d-f sp-bw al-it-cent ">
          <!-- left -->
          <div>
              <img class="head-logo" src="@/assets/dc-logo.png" alt="">
          </div>
          <!-- right -->
          <div>
              <!-- lista -->
              <ul class="d-f li-st t-t-upp ">
                  <li v-for="(link, index) in HeaderLink" :key="`link-${index}`">
                      <a href="#" class="tx-dec">{{link.name}}</a>
                  </li>
              </ul>
          </div>
      </div>

  </section>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return{
            HeaderLink: [
                {
                    name: 'characters',
                },
                {
                    name: 'comics',
                },
                {
                    name: 'movies',
                },
                {
                    name: 'tv',
                },
                {
                    name: 'games',
                },
                {
                    name: 'collectibles',
                },
                {
                    name: 'videos',
                },
                {
                    name: 'fans',
                },
                {
                    name: 'news',
                },
                {
                    name: 'news',
                },
                {
                    name: 'shop',
                },
            ]
        }
    }
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
    font-weight: 400;

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
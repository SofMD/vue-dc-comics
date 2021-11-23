<template>
  <section>
      <div class="container">
          <ul class="d-f li-st t-t-upp ">
                <li class="d-f al-it-cent c-pointer">
                    <img src="@/assets/buy-comics-digital-comics.png" alt="">
                    <span>digital comics</span>
                </li>
                <li class="d-f al-it-cent c-pointer">
                    <img src="@/assets/buy-comics-merchandise.png" alt="">
                    <span>dc merchandise</span>
                </li>
                <li class="d-f al-it-cent c-pointer">
                    <img src="@/assets/buy-comics-subscriptions.png" alt="">
                    <span>subscription</span>
                </li>
                <li class="d-f al-it-cent c-pointer">
                    <img src="@/assets/buy-comics-shop-locator.png" alt="">
                    <span>comic shop locator</span>
                </li>
                <li class="d-f al-it-cent c-pointer ">
                    <img src="@/assets/buy-dc-power-visa.svg" alt="">
                    <span>dc power visa</span>
                </li>
                

          </ul>
      </div>
  </section>
</template>

<script>
export default {
    name: 'Nav'
}
</script>


<style scoped lang="scss">
@import '@/style/variables.scss';

section {
    background-color: $base-blue;
    color: white;
    padding: 40px 0;

    .container {

        ul{
            justify-content: space-around;

            img{
                 width: 50px;
            }
            span {
                 margin-left: 15px;
                 font-size: 15px;
            }
    
        }
    }
}


</style>
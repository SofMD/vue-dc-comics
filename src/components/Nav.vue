<template>
  <section>
      <div class="container">
          <ul>
                <li>
                    <img src="@/assets/buy-comics-digital-comics.png" alt="">
                    <span>digital comics</span>
                </li>
                <li>
                    <img src="@/assets/buy-comics-merchandise.png" alt="">
                    <span>dc merchandise</span>
                </li>
                <li>
                    <img src="@/assets/buy-comics-subscriptions.png" alt="">
                    <span>subscription</span>
                </li>
                <li>
                    <img src="@/assets/buy-comics-shop-locator.png" alt="">
                    <span>comic shop locator</span>
                </li>
                <li>
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

section {
    background-color: #0082f3;
    color: white;
    padding: 40px 0;

    .container {

        ul{
            list-style: none;
            display: flex;
            justify-content: space-around;

            li{
                text-transform: uppercase;
                display: flex;
                align-items: center;


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
}


</style>
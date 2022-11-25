<template>
  <header>
    <div class="containerGray">
      <div class="banner">
            <!-- <cardTest
            v-for="i in 10"
            :key="i"
            class="card-test"
            /> -->
      </div>
      <div class="container">
        <div class="content">
          ciao
        </div>
      </div>
    </div>
    <div class="containerBlue">
        <div class="container">
          <div class="boxImgText">
              <div class="logo">
                <img src="@/components/img/buy-comics-digital-comics.png" alt="">
              </div>
              <div>DIGITAL COMICS</div>
          </div>
          <div class="boxImgText">
              <div class="logo">
                <img src="@/components/img/buy-comics-merchandise.png" alt="">
              </div>
              <div>DC MERCHANDISE</div>
          </div>
          <div class="boxImgText">
              <div class="logo">
                <img src="@/components/img/buy-comics-subscriptions.png" alt="">
              </div>
              <div>SUBSCRIPTION</div>
          </div>
          <div class="boxImgText">
              <div class="logo">
                <img src="@/components/img/buy-comics-shop-locator.png" alt="">
              </div>
              <div>COMICS SHOP LOCATOR</div>
          </div>
          <div class="boxImgText">
              <div class="logo" id="special">
                <img src="@/components/img/buy-dc-power-visa.svg" alt="">
              </div>
              <div>DC POWER VISA</div>
          </div>
        </div>
    </div>
  </header>
</template>

<script>

export default {
};
</script>

<style lang="scss" scoped>

  .container{
      width: 70%;
      height: 100%;
      margin: auto;
      display: flex;
      align-items: center;
      color: white;
  }
  .containerGray{
        width: 100%;
        height: 1200px;
        background-color: rgb(33, 33, 33);

  }
  .containerBlue{
        width: 100%;
        height: 15vh;
        background-color: rgba(2,130,249,255);
  }
  .banner{
      height: 40%;
      width: 100%;
      color: white;
      background-image: url("@/components/img/jumbotron.jpg");
  }

  .content{
    height: 50%;
      width: 100%;
      color: white;
  }

  img{
      width: 40%;
      height: 40%;
      object-fit: contain;
      display: flex;
      justify-content: center;
      align-items: center;
  }

  #special{
      width: 40%;
      height: 40%;
  }

  .boxImgText{
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 20px;
      width: 20%;
  }

  .logo{
      display: flex;
      justify-content: flex-end;
      align-items: center;
  }

</style>

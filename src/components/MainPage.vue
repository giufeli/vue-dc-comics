<template>
  <header>
    <div class="containerGray">
      <div class="banner"></div>
      <div class="content">
          <div class="series">CURRENT SERIES</div>
          <cardBox
            v-for="i in arrComics"
            :key="i.series"
            :series="i.series"
            :comics="i"
          />
          <button>LOAD MORE</button>
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

import cardBox from '@/components/cardBox.vue';

export default {

  components: {
    cardBox,
  },
  data() {
    return {
      arrComics: [
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX',
          price: '$19.99',
          series: 'Action Comics',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01',
          price: '$3.99',
          series: 'American Vampire 1976',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb',
          price: '$16.99',
          series: 'Aquaman',
          type: 'graphic novel',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76',
          price: '$2.99',
          series: 'Batgirl',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ',
          price: '$3.99',
          series: 'Batman',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ',
          price: '$2.99',
          series: 'Batman Beyond',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8',
          price: '$3.99',
          series: 'Batman/Superman',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk',
          price: '$4.99',
          series: 'Batman/Superman Annual',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8',
          price: '$5.99',
          series: 'Batman: The Joker War Zone',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY',
          price: '$6.99',
          series: 'Batman: Three Jokers',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX',
          price: '$4.99',
          series: 'Batman: White Knight Presents: Harley Quinn',
          type: 'comic book',
        },
        {
          thumb: 'https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq',
          price: '$16.99',
          series: 'Catwoman',
          type: 'graphic novel',
        },
      ],
    };
  },
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
        height: 1100px;
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
      position: relative;
      width: 70%;
      height: 60%;
      margin: auto;
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      flex-wrap: wrap;
      gap:10px;
      padding-top:20px
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

  button{
    background-color: rgba(2,130,249,255);
    padding: 13px 70px;
    border: solid 2px rgba(2,130,249,255);
    color: white;
    font-size: 15px;
    margin-bottom: 10px;
  }

  .series{
    position: absolute;
    top:0;
    margin-top: -25px;
    left: 0;
    height: 45px;
    width: 190px;
    background-color: rgba(2,130,249,255);
    color: white;
    font-size: 20px;
    display: flex;
    justify-content: center;
    align-items: center;

  }

</style>

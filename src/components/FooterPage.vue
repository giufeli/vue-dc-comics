<template>
  <header>
    <div class="background">
      <div class="container">
        <div class="boxList">
          <div class="column">
            <div class="title">DC COMICS</div>
            <ul>
              <li>Characters</li>
              <li>Comics</li>
              <li>Movies</li>
              <li>TV</li>
              <li>Games</li>
              <li>Videos</li>
              <li>News</li>
            </ul>
            <div class="title">SHOP</div>
            <ul>
              <li>Shop DC</li>
              <li>Shop DC Collectibles</li>
            </ul>
          </div>
          <div class="column">
            <div class="title">DC</div>
            <ul>
              <li>Term of use</li>
              <li>Privacy Policy (New)</li>
              <li>Ad Choices</li>
              <li>Advertising</li>
              <li>Jobs</li>
              <li>Subscription</li>
              <li>Talent Workshop</li>
              <li>CPSC Certificates</li>
              <li>Ratings</li>
              <li>Shop Help</li>
              <li>Contacts Us</li>
            </ul>
          </div>
          <div class="column">
            <div class="title">SITES</div>
            <ul>
              <li>DC</li>
              <li>MAD Magazine</li>
              <li>DC Kids</li>
              <li>DC Universe</li>
              <li>DC Power Visa</li>
            </ul>
          </div>
        </div>
        <div class="boxBigLogo"><img src="@/components/img/dc-logo-bg.png" alt=""></div>
      </div>

    </div>
    <div class="containerGray">
        <div class="container">
          <div class="boxButton">
            <button>SING-UP NOW!</button>
          </div>
          <div class="boxSocial">
            <div class="follow">FOLLOW US</div>
            <div class="boxIcon">
                <div><img src="@/components/img/footer-facebook.png" alt=""></div>
                <div><img src="@/components/img/footer-twitter.png" alt=""></div>
                <div><img src="@/components/img/footer-youtube.png" alt=""></div>
                <div><img src="@/components/img/footer-pinterest.png" alt=""></div>
                <div><img src="@/components/img/footer-periscope.png" alt=""></div>

            </div>
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
.background{
  width: 100%;
  height: 42vh;
  display: flex;
  background-image: url("@/components/img/footer-bg.jpg");
}
.container{
  width: 70%;
  height: 100%;
  margin: auto;
  display: flex;
  justify-content: space-between;
}

img{
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.boxList{
  width: 35%;
  height: 100%;
  display: flex;
}
.column{
  height: 100%;
  width: 33%;
}

.boxBigLogo{
  width: 50%;
  height: 100%;
}

.title{
  color: white;
  font-size: 23px;
  margin-top: 30px;
}

ul{
  font-size: 13px;
  color: rgb(159, 159, 159);
  padding-inline-start: 0px;
}

li{
  list-style: none;
  padding-bottom: 8px;
}

.containerGray{
  width: 100%;
  height: 10vh;
  background-color: rgb(58, 58, 58);
}

.boxButton{
  width: 50%;
  height: 100%;
  display: flex;
  align-items: center;
  margin-top: auto;
  margin-bottom: auto;
}

.boxSocial{
  width: 30%;
  height: 100%;
  display: flex;
  justify-content: flex-end ;
  align-items: center;
  margin-top: auto;
  margin-bottom: auto;
}

button{
  background-color: rgb(58, 58, 58);
  padding: 13px;
  border: solid 2px rgba(2,130,249,255);
  color: white;
  font-size: 15px;
}

.follow{
  width: 30%;
  color: rgba(2,130,249,255);
  font-size: 20px;
  margin-right: 20px;
}

.boxIcon{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 70%;
}

.icon{
  width: 20%;
  height: 50%;
}

</style>

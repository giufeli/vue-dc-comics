<template>
  <div>
    <HeaderPage />
    <MainPage />
    <FooterPage />
  </div>
</template>

<script>
import HeaderPage from '@/components/HeaderPage.vue';
import MainPage from '@/components/MainPage.vue';
import FooterPage from '@/components/FooterPage.vue';

export default {

  components: {
    HeaderPage,
    MainPage,
    FooterPage,
  },
};

</script>

 <style lang="scss">
   @import url("https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap");

   html{
     font-family: 'Roboto', sans-serif;

   }

   body{
     margin: 0;
     padding: 0;
     box-sizing: border-box;
     background-color: black;
   }

   a{
     text-decoration: none;
     color: black;
   }

   a:hover{
     color:  #0091ff;
   }

 </style>

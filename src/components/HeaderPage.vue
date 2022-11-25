<template>
  <header>
    <div class="navbar">
        <div class="container">
            <div class="imgBox">
                <img src="@/components/img/dc-logo.png" alt="">
            </div>
            <div class="boxMenu">
                <ul>
                    <li><a href="">CHARACTERS</a></li>
                    <li><a href="">COMICS</a></li>
                    <li><a href="">MOVIES</a></li>
                    <li><a href="">TV</a></li>
                    <li><a href="">GAMES</a></li>
                    <li><a href="">COLLECTIBLES</a></li>
                    <li><a href="">VIDEOS</a></li>
                    <li><a href="">FANS</a></li>
                    <li><a href="">NEWS</a></li>
                    <li><a href="">SHOP</a></li>
                </ul>
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
        justify-content: space-between;
    }
    .navbar{
        width: 100%;
        height: 12vh;
        background-color: white;
    }

    img{
        width: 100%;
        height: 100%;
        object-fit: cover;
    }

    ul{
        display: flex;
        list-style: none;
        gap: 30px;
        font-size: 15px;
    }
    .imgBox{
        margin-top: auto;
        margin-bottom: auto;
    }

    .boxMenu{
        display: flex;
        justify-content: flex-end;
        align-items: center;
    }
</style>

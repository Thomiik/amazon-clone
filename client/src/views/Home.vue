<template>
<div class="container">
  <div id="home-content">
    <div id="home-slideshow">
      <h1 style="text-align: center; padding-bottom: 50px;">SlideShow</h1>
    </div>
    <div id="home-pics3-signin">

    </div>
    <div class="home-pics4">
      <span class="home-pic">
        <h1 class="home-pic-header">Test 1</h1>
        <img src="https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Fuji/2020/May/Dashboard/Fuji_Dash_PC_1x._SY304_CB431800965_.jpg">
        <router-link class="home-pic-link" to="/category">See More</router-link>
      </span>
      <span class="home-pic">
        <h1 class="home-pic-header">Test 2</h1>
        <img src="https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Fuji/2020/May/Dashboard/Fuji_Dash_PC_1x._SY304_CB431800965_.jpg">
        <router-link class="home-pic-link" to="/category">See More</router-link>
      </span>
      <span class="home-pic">
        <h1 class="home-pic-header">Test 3</h1>
        <img src="https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Fuji/2020/May/Dashboard/Fuji_Dash_PC_1x._SY304_CB431800965_.jpg">
        <router-link class="home-pic-link" to="/category">See More</router-link>
      </span>
      <span class="home-pic">
        <h1 class="home-pic-header">Test 4</h1>
        <img src="https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Fuji/2020/May/Dashboard/Fuji_Dash_PC_1x._SY304_CB431800965_.jpg">
        <router-link class="home-pic-link" to="/category">See More</router-link>
      </span>
    </div>
    <div class="home-line">
      <h1 style="text-align: center; padding-bottom: 50px;">Home Line</h1>
    </div>
  </div>
</div>
</template>

<script>
</script>

<style lang="scss" scoped>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
  $home-bgc: #eaeded;
  $link-color: #007185;

  .container {
    height: 1000px;
    background-color: $home-bgc;
    font-family: 'Roboto', sans-serif;
  }

  #home-content {
    justify-content: center;
    @media screen and (min-width: 1500px) {
      max-width: 1500px;
      margin: 0 calc((100vw - 1500px)/2);
    }
    // background-color: blue;

    #home-slideshow {
      // passs
    }

    // 1480
    // 340px x 420px (+ padding 20px 0 15px)
    .home-pics4 {
      display: flex;
      max-width: 1480px;
      justify-content: center;
      margin: 10px;
      gap: 20px;
      .home-pic {
        box-shadow: 0 0 3px rgb(185, 185, 185);
        background-color: #ffffff;
        width: 340px;
        padding: 20px 0 15px;
        height: 400px;

        .home-pic-header {
          margin-left: 20px;
          font-size: 1.2em;
        }

        .home-pic-link {
          font-size: 0.9em;
          margin-left: 20px;
          text-decoration: none;
          color: $link-color;
        }

        img {
          object-fit: cover;
          object-position: center;
          margin: 16px 0 16px 20px;
          width: 300px;
          height: 300px;
        }
      }
    }
  }
</style>

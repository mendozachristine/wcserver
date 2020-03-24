<template>
<div>>
    <header class="py-5 bg-image-full" style="background-image: url('https://wallpaperplay.com/walls/full/2/c/8/144502.jpg');">
    <img class="img-fluid" style="height: 200px; width:200px; margin-left:575px;" src="../assets/logocm.png" alt="">
  </header>

  <!-- Content section -->
  <section class="py-5">
    <div class="container">
      <h1>FEATURED</h1>
      <br>
      <br>
      <br>
      <br>
     <div class ="news1"><img src="https://dy6g3i6a1660s.cloudfront.net/7O72IIJK3lFCgQW6J2yPYgeoBLA/mb-c4/best-dark-circle-concealers.jpg" alt=""><a href="#">5 Concealers That Actually Camouflage Dark Circles</a></div>
     <div class ="news2"><img src="https://dy6g3i6a1660s.cloudfront.net/qkAKuYm1gzA9oQhVy4DM0AeoBLA/mb-40/makeup-to-match-your-bubbly.jpg" alt=""><a href="#">Makeup to Match Your Bubbly</a></div>
    </div>
  </section>

  <!-- Image Section - set the background image for the header in the line below -->
 <!--  <section class="py-5 bg-image-full" style="background-image: url('../assets/banner.jpg');"> 
     Put anything you want here! There is just a spacer below for demo purposes! -->
   <!--  <div style="height: 200px;"></div> 
  </section> -->

 <!-- Content section -->
 <!--  <section class="py-5">
    <div class="container">
      <h1>Section Heading</h1>
      <p class="lead">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid, suscipit, rerum quos facilis repellat architecto commodi officia atque nemo facere eum non illo voluptatem quae delectus odit vel itaque amet.</p>
    </div>
  </section> -->
</div>

</template>

<script>
export default {
  name: 'home',

}
</script>

<style scoped>
@font-face {
  font-family: Calisto;
  src: url(/fonts/CalistoMT.ttf);
}
h1 {
  font-family: Calisto;
  font-size: 40px;
  font-style: italic;
  font-weight: bold;
  text-decoration: underline;
  text-align: center;
}

.container {
  display: block;
  text-align: center;
}

.news1 {
  float: left;
  margin-right: 200px;
}

.news1 a, .news2 a {
  display: block;
  text-align: center;
  font-family: Calisto;
  font-size: 23px;  
  font-weight: bold;
  font-style: italic;
  text-decoration: underline;
  color: rgb(46, 46, 46);
  padding-top: 10px;
  margin-bottom: 100px;
}

.img-fluid {
  width: 100%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}


</style>

<template>
  <footer>
    <section class="one">
      <div class="container">
        <div class="link">
          <ul>
            <h2> DC COMICS </h2>
              <li><a href="#">Characters</a></li>
              <li><a href="#">Comics</a></li>
              <li><a href="#">Movies</a></li>
              <li><a href="#">Tv</a></li>
              <li><a href="#">Games</a></li>
              <li><a href="#">Videos</a></li>
              <li><a href="#">News</a></li>
          </ul>

          <ul>
            <h2>DC</h2>
              <li><a href="#">Terms of Use</a></li>
              <li><a href="#">Privacy policy(new)</a></li>
              <li><a href="#">Ad Choices</a></li>
              <li><a href="#">Advertising</a></li>
              <li><a href="#">Jobs</a></li>
              <li><a href="#">Subscriptions</a></li>
              <li><a href="#">Talent Workshop</a></li>
              <li><a href="#">CPSC Certificates</a></li>
              <li><a href="#">Ratings</a></li>
              <li><a href="#">Shop Help</a></li>
              <li><a href="#">Contact Us</a></li>
          </ul>
          <ul>
            <h2> SITES</h2>
              <li><a href="#">DC</a></li>
              <li><a href="#">MAD Magazine</a></li>
              <li><a href="#">DC Kids</a></li>
              <li><a href="#">DC Universe</a></li>
              <li><a href="#">DC Power Visa</a></li>
          </ul>
          <ul>
            <h2> SHOP </h2>
              <li><a href="#">Shop DC</a></li>
              <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
          
        </div>
        <div class="logodc">
        </div>

      </div>
      <div class="two">
          <div class="container">
            <button><a href="#"></a>SIGN UP NOW!</button>
            <div class="follow">
              <div>FOLLOW US</div>
              <img src="../assets/img/footer-facebook.png" alt="logo Facebook">
              <img src="../assets/img/footer-twitter.png" alt="logo Twitter">
              <img src="../assets/img/footer-youtube.png" alt="Logo Youtube">
              <img src="../assets/img/footer-pinterest.png" alt="logo P">
              <img src="../assets/img/footer-periscope.png" alt="Logo Localizzazione">
            </div>
          </div>
      </div>
    </section>
  </footer>
</template>

<script>
export default {
name:"Footer"
}
</script>

<style lang="scss" scoped>
@import '../assets/style/partials/variables.scss';
.one {
  height:400px;
  background-image: url("../assets/img/footer-bg.jpg");
  background-position: center;
  background-size: cover;
    .logodc {
      height:350px;
      background-image: url("../assets/img/dc-logo-bg.png");
      background-repeat: no-repeat;
      background-position:90%,right;
    }
  .link {
    width:50%;
      ul {
      float:left;
      color:white;
      text-align: center;
      margin:0 15px;
      padding-top:30px;
      li {
        list-style: none;
        h2 {
          font-size:20px;
        }
        a {
          font-size: 12px;
          text-decoration: none;
          color:grey;
          margin:20px;
          
        }
        
      }
        
    }
  }
    img {
      height:300px;
      float:right;
      padding-right: 90px;
    }



  

    
}

.two {
  height:120px;
  background-color: #303030;
  display:flex;
  align-items: center;
  .container {
    display:flex;
    justify-content: space-between;
    button {
      color:white;
      text-transform: uppercase;
      background-color: #303030;
      padding:8px;
      border:2px solid $mainColor;
    }
    .follow{
      width:70%;
      display:flex;
      align-items: center;
      div {
        font-size: 20px;
        color:$mainColor;
        padding-right: 20px;
      }
      img {
      height:30px;
    }}
  }
  
  } 


</style>
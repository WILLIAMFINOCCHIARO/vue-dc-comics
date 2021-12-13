<template>
  <main>
    <section class=" one">
      <div class="container">
        <a href="#">
          -- content goes here --
        </a>
      </div>

    </section> 

    <section class="main two">
      <div class="container">
        <ul>
          <li> <img src="../assets/img/buy-comics-digital-comics.png" alt=""> <a href="#">digital comics</a></li>
          <li> <img src="../assets/img/buy-comics-merchandise.png" alt=""> <a href="#">dc merchandise</a></li>
          <li> <img src="../assets/img/buy-comics-shop-locator.png" alt=""> <a href="#">subscription</a></li>
          <li> <img src="../assets/img/buy-comics-subscriptions.png" alt=""> <a href="#">comic shop locator</a></li>
          <li> <img src="../assets/img/buy-dc-power-visa.svg" alt=""> <a href="#">dc power visa</a></li>
        </ul>
      </div>
      
    </section>
  </main>
</template>

<script>
export default {
name:"Main",
}
</script>

<style lang="scss" scoped>
@import '../assets/style/partials/variables.scss';
section {
  height:200px;  
}

.one {
  background-color: black;
  a {
    color:white;
    font-size: 50px;
    line-height:200px;
    text-decoration: none;
    text-transform: capitalize;
    cursor: pointer;
  }
}

.two {
  background-color: $mainColor;
  ul{
  display: flex;
  justify-content: space-around;
  line-height: 200px;
      li {
    list-style:none;
    display: flex;
      img {
        height:100px;
        align-self: center;
      }
      a {
        color:white;
        text-decoration: none;
        text-transform:uppercase;
      }
  }

  }
  
}

</style>
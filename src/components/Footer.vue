<template>
  <footer>
    <section class="one">
      <div class="container">
        <div class="link">
          <ul>
            <h2> dc comics </h2>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aa</a></li>
              <li><a href="#">aaa</a></li>
          </ul>

          <ul>
            <h2>dc</h2>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aa</a></li>
              <li><a href="#">aaa</a></li>
          </ul>
          <ul>
            <h2> sites</h2>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aa</a></li>
              <li><a href="#">aaa</a></li>
          </ul>
          <ul>
            <h2> shop </h2>
              <li><a href="#">aaa</a></li>
              <li><a href="#">aaa</a></li>
          </ul>
          
        </div>
        <div class="logodc">
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
    width:40%;
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
          text-transform: uppercase;
        }
        a {
          font-size: 15px;
          text-decoration: none;
          color:grey;
          margin:20px;
          
        }
        
      }
        
    }
  }
    img {
      height:500px;
      float:right;
      padding-right: 90px;
    }

    
}
</style>
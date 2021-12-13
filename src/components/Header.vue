<template>
  <header>
    <div class="container header">
      <div class="logo">
        <img src="../assets/img/dc-logo.png" alt="logo DC">
      </div>
      <nav>
        <ul>
          <li><a href="#">characters</a></li>
          <li><a href="#">comics</a></li>
          <li><a href="#">movies</a></li>
          <li><a href="#">tv</a></li>
          <li><a href="#">games</a></li>
          <li><a href="#">collectibles</a></li>
          <li><a href="#">videos</a></li>
          <li><a href="#">fans</a></li>
          <li><a href="#">news </a></li>
          <li><a href="#">shop</a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
name:"Header",
}
</script>

<style lang="scss" scoped>
  .container.header {
    height:200px;
    padding:20px;
  }


  .logo {
    float:left;
    &:after {
      display:table;
      content:"";
      clear:both;
    }
    img {
    height:100px;
  }};

  nav {
    float:right;
    height:100px;
    display:flex;
    align-items: center;
    ul {
      li {
      list-style: none;
      display:inline-block;
      margin: 0 10px;
      a {
        text-decoration: none;
        color:#5d5e5f;
        &:hover{
        color:blue;
        padding-bottom:100px;
        border-bottom: 2px solid blue;
        }
      }
      
      };
    }
  };



</style>


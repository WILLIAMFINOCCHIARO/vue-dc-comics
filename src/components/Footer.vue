<template>
  <footer>
    <section class="one">
      <div class="dc">
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
    .dc {
      height:350px;
      background-image: url("../assets/img/dc-logo-bg.png");
      background-repeat: no-repeat;
      background-position:90%,right;
    }
    ul {
      float:left;
    }
    img {
      height:500px;
      float:right;
      padding-right: 90px;
    }
}
</style>
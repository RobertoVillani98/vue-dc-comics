<template>
  <header>
    <div class="container">
      <div class="logo">
        <img src="../../assets/img/dc-logo.png" alt="Logo dc" />
        <nav>
          <ul>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">Tv</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Collectibles</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">Fans</a></li>
            <li><a href="#">News</a></li>
            <li><a href="#">Shop</a></li>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/partials/variables.scss";
header {
  margin-top: 20px;
  text-align: center;
  margin-bottom: 20px;
}
.container {
  width: 80%;
  margin: 0 auto;
  display: flex;
  justify-content: space-around;
}
.logo {
  display: flex;
  img {
    height: 70px;
    margin-right: 200px;
  }
}
nav {
  margin-top: 10px;
  ul {
    display: flex;
    list-style: none;
    li a {
      text-transform: uppercase;
      font-weight: 500;
      font-size: 14px;
      display: inline-block;
      padding: 15px 20px;
      text-decoration: none;
      color: #000;
      &.active,
      &:hover {
        border-bottom: 4px solid $mainColor;
      }
    }
  }
}
</style>

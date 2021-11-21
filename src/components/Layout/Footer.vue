<template>
  <footer>
    <img class="footer-img" src="@/assets/img/footer-img.png" />
    <div class="footer-bg">
      <img src="@/assets/img/bike_logo.png" alt="" class="d-inline-block align-text-top mx-1" />
      <img src="@/assets/img/Taiwan_logo.png" alt="" class="d-inline-block align-text-top mx-1" />
      <div>©2021 , Taiwan Bike. All Rights Reserved.</div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer'
};
</script>

<style lang="scss" scoped>
footer {
  background-color: $bg;
}
.footer-img {
  width: 100%;
}

.footer-bg {
  background-color: #363636;
  color: #ffffff;
  padding: 60px;
  img {
    height: 22px;
  }
}
</style>

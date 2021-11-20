<template>
  <nav class="navbar c-bg">
    <div class="container">
      <a class="navbar-brand" href="#">
        <img src="@/assets/img/bike_logo.png" alt="" class="d-inline-block align-text-top mx-1" />
        <img src="@/assets/img/Taiwan_logo.png" alt="" class="d-inline-block align-text-top mx-1" />
      </a>
      <ul class="nav justify-content-end">
        <li class="nav-item">
          <a class="nav-link active text-white fw-bold" aria-current="page" href="#">首頁</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-white fw-bold" href="#">站點資訊</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-white fw-bold" href="#">路線導覽</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-white fw-bold disabled">最新消息</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Header'
};
</script>

<style lang="scss" scoped>
.c-bg {
  height: 80px;
  background-color: $primary;
  color: #ffffff;
}
.navbar-brand {
  img {
    height: 24px;
  }
}

.nav-link.active {
    color: $secondary !important;
}
</style>

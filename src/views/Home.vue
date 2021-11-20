<template>
  <div class="home">
    <section class="banner">
      <div class="banner-center">
        <div class="banner-img">
          <img class="go-img" src="@/assets/img/go.png" />
          <img class="word-img" src="@/assets/img/banner_word.png" />
        </div>
        <div class="desc">
          <p>
            台灣的各個美景，都美不勝收。
            <br />
            等你一同來發現這座寶島的奧妙！
          </p>
        </div>
      </div>
    </section>
    <section class="c-section container">
      <h4 class="text-center title">最新消息</h4>
      <div class="c-card mt-5">
        <div class="activity-card row">
          <div class="col-md-2 col-3 new">NEW</div>
          <div class="col-md-2 col-4 black-word fw-bold">最新活動</div>
          <div class="col-md-2 col-5 black-word">2021/11/2-11/3</div>
          <div class="col-md-6 col-12 gray-word">台北西湖 YouBike 站點因定期保養，停止租借服務一天</div>
        </div>
        <div class="activity-card row">
          <div class="col-md-2 col-3 new">NEW</div>
          <div class="col-md-2 col-4 black-word fw-bold">最新活動</div>
          <div class="col-md-2 col-5 black-word">2021/11/2-11/3</div>
          <div class="col-md-6 col-12 gray-word">台北西湖 YouBike 站點因定期保養，停止租借服務一天</div>
        </div>
        <div class="activity-card row">
          <div class="col-md-2 col-3 new">NEW</div>
          <div class="col-md-2 col-4 black-word fw-bold">最新活動</div>
          <div class="col-md-2 col-5 black-word">2021/11/2-11/3</div>
          <div class="col-md-6 col-12 gray-word">台北西湖 YouBike 站點因定期保養，停止租借服務一天</div>
        </div>
        <button type="button" class="btn btn-primary mt-4">See More</button>
      </div>
    </section>
    <section class="c-section container">
      <h4 class="text-center title">熱門路線</h4>
      <p class="gray-word mt-4">台灣的各個美景，都美不勝收。等你一同來發現這座寶島的奧妙！</p>
      <div class="row hot-path mt-5">
        <div class="col-md-6 col-12 cur-pointer">
          <img src="@/assets/img/path/path1.png" />
        </div>
        <div class="col-md-6 col-12 cur-pointer">
          <img src="@/assets/img/path/path2.png" />
        </div>
        <div class="col-md-6 col-12 cur-pointer">
          <img src="@/assets/img/path/path3.png" />
        </div>
        <div class="col-md-6 col-12 cur-pointer">
          <img src="@/assets/img/path/path4.png" />
        </div>
      </div>
    </section>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {}
};
</script>

<style lang="scss" scoped>
.home {
  background-color: #f8f9fb;
}
.banner {
  background-image: url('../assets/img/bg.png');
  width: 100%;
  height: calc(100vh - 80px);
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
}

.banner-center {
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: center;

  .banner-img {
    position: relative;
    width: 70%;
    margin: 0 auto;
  }

  .go-img {
    position: absolute;
    height: 120px;
    left: 0px;
    top: -50px;
  }

  .word-img {
    width: 100%;
  }

  .desc {
    color: #ffffff;
    font-weight: 900;
    font-size: 21px;
  }
}

.c-section {
  padding: 150px 0;
}

.title {
  color: $primary;
  font-weight: 900;
  font-size: 32px;
}

.c-card {
  background: #ffffff;
  box-shadow: 4px 16px 38px rgba(165, 165, 165, 0.15);
  border-radius: 16px;
  padding: 70px 120px;
}

.activity-card {
  background-color: $primary-light;
  margin: 20px 0;
  padding: 20px;
  text-align: left;

  .new {
    color: $primary-2;
    font-weight: 900;
  }
}

.black-word {
  color: $black;
}

.gray-word {
  color: $gray;
}

.hot-path {
  img {
    width: 100%;
  }
}

@media screen and (max-width: 768px) {
  .c-card {
    padding: 25px;
  }

  .activity-card {
    padding: 20px 10px;
  }
}
</style>

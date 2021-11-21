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
    <!-- 最新消息 -->
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
    <!-- 熱門路線 -->
    <section class="c-section container">
      <h4 class="text-center title">熱門路線</h4>
      <p class="gray-word mt-4">台灣的各個美景，都美不勝收。等你一同來發現這座寶島的奧妙！</p>
      <div class="row hot-path mt-5">
        <div class="col-md-6 col-12 cur-pointer my-2">
          <img src="@/assets/img/path/path1.png" />
        </div>
        <div class="col-md-6 col-12 cur-pointer my-2">
          <img src="@/assets/img/path/path2.png" />
        </div>
        <div class="col-md-6 col-12 cur-pointer my-2">
          <img src="@/assets/img/path/path3.png" />
        </div>
        <div class="col-md-6 col-12 cur-pointer my-2">
          <img src="@/assets/img/path/path4.png" />
        </div>
      </div>
    </section>
    <!-- 附近站點 -->
    <section class="c-section container">
      <h4 class="text-center title">附近站點</h4>
      <p class="gray-word mt-4">最近的站點資訊。</p>
      <div class="row near-step mt-5">
        <div class="col-md-7 col-12 cur-pointer">
          <Map></Map>
        </div>
        <div class="col-md-5 step-info">
          <div class="step">東海大學站</div>
          <div class="place gray-word">地址: 台中市西屯區台灣大道四段1727號</div>
          <div class="d-flex mt-2 mb-5">
            <div class="d-flex mt-2 align-items-center">
              <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M9 18C13.9706 18 18 13.9706 18 9C18 4.02944 13.9706 0 9 0C4.02944 0 0 4.02944 0 9C0 13.9706 4.02944 18 9 18ZM14.4073 6.38761C14.8285 5.93083 14.7996 5.21911 14.3428 4.79793C13.886 4.37675 13.1743 4.40561 12.7531 4.86239L7.84205 10.1886L5.2955 7.64201C4.85616 7.20267 4.14385 7.20267 3.70451 7.642C3.26517 8.08134 3.26516 8.79365 3.7045 9.23299L6.25105 11.7796C7.15502 12.6836 8.6296 12.6537 9.4962 11.7138L14.4073 6.38761Z"
                  fill="#28C0F0"
                />
              </svg>
              <span class="mx-2">狀態 : 營業中</span>
            </div>
            <div class="d-flex mt-2 align-items-center">
              <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M8.5425 7.7926L5.625 10.7078L2.7075 7.7926C2.1308 7.21563 1.73813 6.48062 1.57912 5.6805C1.42011 4.88038 1.50192 4.05108 1.81418 3.29745C2.12645 2.54382 2.65517 1.89969 3.33348 1.44652C4.01179 0.993343 4.80924 0.751465 5.625 0.751465C6.44077 0.751465 7.23822 0.993343 7.91653 1.44652C8.59484 1.89969 9.12355 2.54382 9.43582 3.29745C9.74809 4.05108 9.82989 4.88038 9.67088 5.6805C9.51188 6.48062 9.1192 7.21563 8.5425 7.7926ZM5.625 6.3751C6.02283 6.3751 6.40436 6.21706 6.68566 5.93576C6.96697 5.65445 7.125 5.27292 7.125 4.8751C7.125 4.47727 6.96697 4.09574 6.68566 3.81444C6.40436 3.53313 6.02283 3.3751 5.625 3.3751C5.22718 3.3751 4.84565 3.53313 4.56434 3.81444C4.28304 4.09574 4.125 4.47727 4.125 4.8751C4.125 5.27292 4.28304 5.65445 4.56434 5.93576C4.84565 6.21706 5.22718 6.3751 5.625 6.3751ZM15.2925 14.5426L12.375 17.4586L9.4575 14.5418C8.8808 13.9649 8.48813 13.2299 8.32912 12.4298C8.17011 11.6296 8.25192 10.8003 8.56418 10.0467C8.87645 9.29307 9.40517 8.64894 10.0835 8.19577C10.7618 7.74259 11.5592 7.50072 12.375 7.50072C13.1908 7.50072 13.9882 7.74259 14.6665 8.19577C15.3448 8.64894 15.8736 9.29307 16.1858 10.0467C16.4981 10.8003 16.5799 11.6296 16.4209 12.4298C16.2619 13.2299 15.8692 13.9656 15.2925 14.5426ZM12.375 13.1251C12.7728 13.1251 13.1544 12.9671 13.4357 12.6858C13.717 12.4045 13.875 12.0229 13.875 11.6251C13.875 11.2273 13.717 10.8457 13.4357 10.5644C13.1544 10.2831 12.7728 10.1251 12.375 10.1251C11.9772 10.1251 11.5956 10.2831 11.3143 10.5644C11.033 10.8457 10.875 11.2273 10.875 11.6251C10.875 12.0229 11.033 12.4045 11.3143 12.6858C11.5956 12.9671 11.9772 13.1251 12.375 13.1251Z"
                  fill="#28C0F0"
                />
              </svg>
              <span class="mx-2">距離 : 12 km</span>
            </div>
          </div>
          <div class="c-bg-primary my-4">
            可租車輛
            <span>11</span>
          </div>
          <div class="c-bg-gray-2 my-4">
            可停車位
            <span>0</span>
          </div>
        </div>
      </div>
    </section>
    <!-- 旅途中美景 -->
    <section class="c-section">
      <h4 class="text-center title">旅途中美景</h4>
      <p class="gray-word mt-4">台灣的各個美景，都美不勝收。等你一同來發現這座寶島的奧妙！</p>
      <img class="view-img mt-5" src="@/assets/img/good_view.png" />
    </section>
  </div>
</template>

<script>
// @ is an alias to /src
import Map from '@/components/Map';
export default {
  name: 'Home',
  components: { Map }
};
</script>

<style lang="scss" scoped>
.home {
  background-color: $bg;
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
  padding: 120px 0;
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

// 附近站點
.near-step {
  background-color: #fff;
  .step-info {
    padding: 70px;
  }
  .step {
    color: $primary-2;
    font-size: 28px;
    font-weight: bold;
    text-align: left;
  }

  .place {
    text-align: left;
    font-size: 16px;
  }
}

// 旅途中美景
.view-img {
  width: 100%;
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

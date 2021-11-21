<template>
  <div id="myMap" class="map-div"></div>
</template>

<script>
export default {
  name: 'Map',
  mounted() {
    this.initMap();
  },
  methods: {
    initMap() {
      // 設定地圖中心點與放大級別
      const map = L.map('myMap', {
        center: [22.595153, 120.306923],
        zoom: 17
      });
      // 載入圖資
      L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
        attribution: '© <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a>contributors'
      }).addTo(map);
      // 彈出視窗
      L.marker([22.595153, 120.306923]).addTo(map).bindPopup('夢時代購物中心').openPopup();
    }
  }
};
</script>

<style lang="scss" scoped>
.map-div {
    width: 100%;
    height: 500px;
}
</style>

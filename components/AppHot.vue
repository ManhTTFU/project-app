<template>
  <div class="app">
    <b-container>
      <b-row class="app-hot">
        <b-col>
          <h1 class="app-title-hot">Hot App</h1>
          <p class="app-content-hot">Welcome to my App Store in DigitalToken Company</p>
        </b-col>
      </b-row>
      <b-row>
        <b-col
        v-for="(App, id) in AppHotData"
        :key="id">
          <a href="#"><img :src="`/img/${App.img}`" /></a>
          <p class="app-hot-price">FREE</p>
          <div class="app-hot-icon">
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>
<script>
import AppHotData from '../filejs/app-hot';

export default {
  data() {
    return {
      AppHotData,
    };
  },
};
</script>

<style>
.app {
  text-align: center;
  background: gainsboro;
  height: 300px;
}
.app-title-hot {
  font-weight: bold;
  color: #4a148c;
  line-height: 15px;
}
.app-content-hot {
  padding-top: 10px;
  color: gray;
}
.app-hot {
  padding-top: 63px;
}
.app-hot-price {
  font-size: 12px;
  color: gray;
  font-weight: bold;
  padding: 10px 50px 0px 0px;
}
.app-hot-icon {
  padding-right: 25px;
}
</style>

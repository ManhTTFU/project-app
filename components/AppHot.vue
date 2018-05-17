<template>
  <div class="app">
    <b-container>
      <b-row class="app-hot">
        <b-col>
          <h1 class="app-title-hot">Hot App</h1>
          <p class="app-content-hot">Welcome to my App Store</p>
        </b-col>
      </b-row>
      <b-row>
        <b-col
        v-for="(App, id) in AppHotData"
        :key="id">
          <a href="#"><img :src="`/img/${App.img}`" /></a>
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
</style>

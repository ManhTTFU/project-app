<template>
  <div class="app-header">
    <b-container fluid="">
      <b-row>
        <b-col>
          <div class="app-header-show">
            <h1 class="title-content">App Store</h1>
            <p>Checking the network cables, modem, and router,fuck your mother ...</p>
            <b-button
              class="btn-one">Buy now</b-button>
            <b-button class="btn-two">Buy now</b-button>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>
<style>
.app {
  height: 200px;
}
.title-content {
  font-size: 50px;
  font-weight: bold;
  color: #616161;
}
.app-header-show p {
  color: #757575;
  font-weight: bold;
}
.app-header {
  background-image: url('../static/img/appstore.jpg');
  background-size: cover;
  height: 91vh;
}
.app-header-show {
  text-align: center;
  padding-top: 420px;
}
.btn-two {
  border-radius: 15px;
  margin-left: 20px;
  width: 145px;
  border: 2px solid black;
  font-weight: bold;
  background: transparent;
}
.btn-two:hover {
  background-color: black;
}
.btn-one {
  border-radius: 15px;
  width: 145px;
  border: 2px solid black;
  font-weight: bold;
  background: transparent;
}
.btn-one:hover {
  background-color: black;
}
</style>

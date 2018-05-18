<template>
  <div class="app-header">
    <b-container fluid="">
      <b-row>
        <b-col>
          <div class="app-header-show">
            <h1 class="title-content">App Store</h1>
            <b-col
              md="6"
              offset="3">
            <b-form-input
            class="search-app"
            id="input-default"
            type="text"
            placeholder="Search app you want to use...">
            </b-form-input>
            </b-col>
            <p>Examplae : facebook, zalo, instagram...</p>
            <b-button
              class="btn-one">Search Now</b-button>
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
  color: black;
  font-weight: bold;
  font-size: 10px;
}
.app-header {
  background-image: url('../static/img/appstore.jpg');
  background-size: cover;
  height: 91vh;
}
.app-header-show {
  text-align: center;
  padding-top: 380px;
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
.search-app {
  border: 3px solid gray;
  border-radius: 20px;
  text-align: center;
}
</style>

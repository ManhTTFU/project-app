<template>
  <div class="product-app mt-5">
    <b-container>
      <b-row>
        <b-col
          v-for="(Product, id) in ProductData"
          :key="id"
          class="spacing-bottom"
          md="3">
              <b-card
                      :img-src="`/img/${Product.img}`"
                      img-alt="Card image"
                      img-top>
                  <div class="show-author">
                    <p class="name-product">{{Product.product}}</p>
                    <p class="name-author">Author : {{Product.name}}</p>
                    <i
                      style="color:yellow"
                      :class="`far ${Product.icon1}`"></i>
                    <i
                      style="color:yellow"
                      :class="`far ${Product.icon2}`"></i>
                    <i :class="`far ${Product.icon3}`"></i>
                  </div>
                  <div>
                    <button class="fas fa-download btn-dowload"></button>
                  </div>
              </b-card>
        </b-col>
    </b-row>
    <paging></paging>
  </b-container>
  </div>
</template>
<script>
import ProductData from '../filejs/product';
import Paging from '../components/Paging';

export default {
  components: {
    Paging,
  },
  data() {
    return {
      ProductData,
    };
  },
};
</script>

<style>
.btn-dowload {
  float: right;
}
.show-author {
  float: left;
}
.name-product {
  margin-bottom: 5px;
  font-weight: bold;
  color: black;
}
.show-author {
  color: darkgrey;
}
.btn-dowload {
  border: 0;
  color: #f48fb1;
  font-size: 25px;
}
.spacing-bottom {
  margin-top: 25px;
}
</style>

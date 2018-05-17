<template>
  <div class="footer-app mt-5">
    <b-container>
      <b-row>
        <b-col
          class="footer-col-left"
          md="4">
          <div class="ft-left">
            <h2>AppStore</h2>
            <p>Lorem Ipsum is simply dummy text of the printing
              and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only
              five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.</p>
          </div>
        </b-col>
        <b-col
          class="footer-col-left-center"
          md="4">
          <h4>Liên Hệ :</h4>
          <i class="far fa-star"><span>Điện thoại :</span> 096 359 0255</i>
          <br>
          <i class="far fa-star"><span>Fax :</span> 0463-4838</i>
          <br>
          <i class="far fa-star"><span>Quảng cáo :</span> 096 968 3333</i>
          <i class="far fa-star"><span>Liên Hệ Quảng cáo :</span> appstore@gmail.com</i>
          <i class="far fa-star"><span>Hỗ trợ :</span> (08) 3910-5018.</i>
          <i class="far fa-star"><span>Email :</span>tuanmanh97x@gmail.com</i>
        </b-col>
        <b-col
          class="footer-col-right"
          md="4">
          <h4>Dowload ứng dụng trên nền tảng website</h4>
          <a
          href="#"
          target="_blank"
          rel="nofollow"
          class="icon_appstore">
          <i
          class="fab fa-apple"
          aria-hidden="true"></i> </a>

          <a
          href="#"
          target="_blank"
          rel="nofollow"
          class="icon_appstore">
          <i
          class="fab fa-android"
          aria-hidden="true"></i> </a>
          <p>Phần mềm và ứng dụng được phát triển bởi công ty DigitalToken</p>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>
<style>
.ft-left {
  width: 90%;
  float: right;
}
.footer-app {
  background-color: #333;
}
.footer-col-left h2 {
  color: white;
  font-weight: bold;
  padding-top: 15px;
}
.footer-col-left p {
  color: #bbb;
  position: relative;
}
.footer-col-left::after {
  content: '';
  position: absolute;
  left: 98%;
  right: 1.79%;
  top: 20px;
  bottom: 20px;
  background: gray;
}
.footer-col-left-center::after {
  content: '';
  position: absolute;
  left: 98%;
  right: 1.79%;
  top: 20px;
  bottom: 20px;
  background: gray;
}
.footer-col-left-center h4 {
  color: white;
  font-weight: bold;
  padding-top: 20px;
}
.footer-col-left-center i {
  color: #bbb;
}
.footer-col-left-center i span {
  color: white;
  font-weight: bold;
  padding-left: 10px;
}
.footer-hr {
  border-left: 1px solid white;
  height: 250px;
  margin-top: 21px;
  width: 0px;
}
.footer-col-right h4 {
  color: white;
  font-weight: bold;
  padding-top: 20px;
  padding-bottom: 15px;
}
i.fab.fa-apple {
  border: 1px solid gray;
  font-size: 65px;
  padding: 13px 20px 13px 20px;
  color: grey;
}
i.fab.fa-android {
  border: 1px solid gray;
  font-size: 65px;
  padding: 13px 20px 13px 20px;
  color: grey;
  margin-left: 20px;
}
.footer-col-right p {
  color: #bbb;
  padding-top: 10px;
  font-size: 15px;
  font-weight: bold;
}
.far.fa-star {
  margin-bottom: 10px;
}
</style>

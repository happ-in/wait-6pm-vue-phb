<template>
<div>
    <v-row no-gutters style="text-align: center">
    <v-col>
      <img class="hana-image" src="https://user-images.githubusercontent.com/36289638/139012300-d5aa3e17-587e-4bc2-925e-d5f64b667e00.png"/>
    </v-col>
    <v-col>
      <img class="hana-image" src="https://user-images.githubusercontent.com/36289638/139013255-f58b0ba0-9d11-4d50-87f1-e7910559062b.png"/>
    </v-col>
    <v-col>
      <img class="hana-image" src="https://user-images.githubusercontent.com/36289638/139013304-b8f1d63d-01a6-4d80-b15c-e9a5cf563c6f.png"/>
    </v-col>
  </v-row>

  <div class="hana-main-gap" />

  <v-row class="hana-main-title justify-center">
		<span>Top collections over &nbsp;</span>
		<span style="color: rgba(25, 139, 131, 1);">last 7 days</span>
    <img src="https://user-images.githubusercontent.com/36289638/139015522-0a82c8b4-7026-42c4-a64f-7f5f87ffd76c.png" alt="">
  </v-row>

  <v-row class="justify-center" style="margin-top: 30px">
    <v-btn elevation="2" x-large class="ranking-btn">
    Go To Rankings
  </v-btn>
  </v-row>

  <div class="hana-main-gap" />

  <div class="container hana-main-text-center">
    <v-row class="hana-main-title justify-center">
      <span style="color: rgba(154, 185, 123, 1);"> / </span>
      금주의 작가
      <span style="color: rgba(154, 185, 123, 1);"> / </span>
    </v-row>
    <div style="text-align: right">
      <a href="#">금주의 작가 더보기 →</a>
    </div>
    <div>
      <img style="width: 1140px;" src="https://user-images.githubusercontent.com/36289638/139017563-f594fc3b-c152-42e5-87c5-3e3ff9da328c.png"/>
    </div>
</div>

</div>
</template>

<script>
export default {

}
</script>

<style>
.hana-image {
   margin: 3%;
    width: 250px;
    height: 300px;
}
.hana-main-title {
  font-size: large;
  font-weight: bold;
}
.hana-main-gap {
  height: 80px;
}
.ranking-btn {
  background-color: rgba(25, 139, 131, 1) !important;
  color: white !important;
  margin: 30px 0px 30px 0px;
}
</style>
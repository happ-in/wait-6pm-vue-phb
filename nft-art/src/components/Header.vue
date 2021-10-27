<template>
  <v-card>
      <v-tabs align-with-title>
        <span class="hana-art-title">하나아트</span>
        <v-tab @click="moveToHome"> Home </v-tab>
        <v-tab @click="moveToNotice"> My Collections </v-tab>
        <v-tab @click="moveToQna"> About </v-tab>
        <v-tab @click="checkLogin"> Create 
            <v-chip class="ma-2" color="purple" text-color="white">New</v-chip>
        </v-tab>
      </v-tabs>
  </v-card>
</template>

<script>
export default {

}
</script>

<style>
.hana-art-title {
    align-self: center;
    width: 100px;
    text-align: center;
    font-size: large;
    margin: 30px;
}
.theme--light.v-tabs > .v-tabs-bar {
    background-color: rgba(25, 139, 131, 1) !important;
    color: white !important;
}
</style>
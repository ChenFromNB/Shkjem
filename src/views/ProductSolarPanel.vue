<template>
  <div class="case">
    <el-image
      style="width: 70%;"
      :src="img1"
      mode="scaleToFill"
    />
    <el-image
      style="width: 70%;"
      :src="img2"
      mode="scaleToFill"
    />
    <el-image
      style="width: 70%;"
      :src="img3"
      mode="scaleToFill"
    />
    <el-image
      style="width: 70%;"
      :src="img4"
      mode="scaleToFill"
    />
    <el-image
      style="width: 70%;"
      :src="img5"
      mode="scaleToFill"
    />
    <el-image
      style="width: 70%;"
      :src="img6"
      mode="scaleToFill"
    />
    <el-image
      style="width: 70%;"
      :src="img7"
      mode="scaleToFill"
    />
    <el-image
      style="width: 70%;"
      :src="img8"
      mode="scaleToFill"
    />
    <el-image
      style="width: 70%;"
      :src="img9"
      mode="scaleToFill"
    />
    <el-image
      style="width: 70%;"
      :src="img10"
      mode="scaleToFill"
    />
    <el-image
      style="width: 70%;"
      :src="img11"
      mode="scaleToFill"
    />
  </div>
</template>

<script>
export default {
  components: {
  },
  data() {
    return {
      img1:require('../assets/img/solar_panel_1.png'),
      img2:require('../assets/img/solar_panel_2.png'),
      img3:require('../assets/img/solar_panel_3.png'),
      img4:require('../assets/img/solar_panel_4.png'),
      img5:require('../assets/img/solar_panel_5.png'),
      img6:require('../assets/img/solar_panel_6.png'),
      img7:require('../assets/img/solar_panel_7.png'),
      img8:require('../assets/img/solar_panel_8.png'),
      img9:require('../assets/img/solar_panel_9.png'),
      img10:require('../assets/img/solar_panel_10.png'),
      img11:require('../assets/img/solar_panel_11.png')
    };
  },
  created() {
  },
  mounted() {
  },
  methods: {
  }
};
</script>

<style lang="scss" scoped>
.case {
  width: 100%;
  height: 100%;
  overflow: hidden;
  background-color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
  &-product {
    width: 1240px;
    margin: 0 auto;
    background-color: #fff;
    //border: 1px solid red;
    &-content {
      width: 760px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      padding: 50px 0;
      img {
        width: 100%;
        height: 430px;
      }
      .product-title {
        font-size: 25px;
        color: #e13834;
        padding: 20px 0;
      }
      .product-content {
        font-size: 17px;
        font-weight: bolder;
        padding: 20px 0;
      }
    }
  }
}
</style>
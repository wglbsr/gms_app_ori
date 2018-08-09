<template>
  <div>
    <mt-header fixed title="长高-德远能源油机管理系统"></mt-header>

    <mt-button class="gms-home-button">
      <img slot="icon" src="../assets/images/icon-test.png">
    </mt-button>

    <mt-button class="gms-home-button">
      <img slot="icon" src="../assets/images/icon-test.png">
    </mt-button>
    <mt-button class="gms-home-button">
      <img slot="icon" src="../assets/images/icon-test.png">
    </mt-button>    <mt-button class="gms-home-button">
    <img slot="icon" src="../assets/images/icon-test.png">
  </mt-button>    <mt-button class="gms-home-button">
    <img slot="icon" src="../assets/images/icon-test.png">
  </mt-button>    <mt-button class="gms-home-button">
    <img slot="icon" src="../assets/images/icon-test.png">
  </mt-button>    <mt-button class="gms-home-button">
    <img slot="icon" src="../assets/images/icon-test.png">
  </mt-button>

    <mt-tabbar v-model="selected">
      <mt-tab-item id="外卖">
        <!--<img slot="icon" src="../assets/100x100.png">-->
        操作
      </mt-tab-item>
      <mt-tab-item id="订单">
        <!--<img slot="icon" src="../assets/100x100.png">-->
        状态
      </mt-tab-item>
      <mt-tab-item id="发现">
        <img slot="icon" src="../assets/images/icon-test.png">
        报表
      </mt-tab-item>
      <mt-tab-item id="我的">
        <i class="el-icon-share"></i>
      </mt-tab-item>
    </mt-tabbar>
  </div>
</template>

<script>
  export default {
    name: "home",
    data() {
      return {
        selected: 0
      }
    }
  }
</script>

<style scoped>
  .gms-home-button {
    height: 100px;
    width: 100px;
    /*margin-left: 1rem;*/
    /*margin-right: 1rem;*/
    float: left;
    margin: 1rem 1rem;
  }

</style>

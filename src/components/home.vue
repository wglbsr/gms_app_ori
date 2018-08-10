<template>
  <grid col="4">wwww
    <grid-item label="Grid" v-for="i in 9">
      <img slot="icon" src="../assets/grid_icon.png">
    </grid-item>
  </grid>
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

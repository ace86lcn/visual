<template>
  <div class="home">
    <top-view></top-view>
    <sales-view></sales-view>
    <bottom-view></bottom-view>
    <map-view></map-view>
  </div>
</template>
<script>
import TopView from '../components/TopView'
import SalesView from '../components/SalesView'
import BottomView from '../components/BottomView'
import MapView from '../components/MapView'
export default {
  components: {
    TopView,
    SalesView,
    BottomView,
    MapView
  }
}
</script>
<style scoped lang="scss">
  .home {
    width: 100%;
    height: 100%;
    padding: 20px;
    background-color: #eee;
    box-sizing: border-box;
  }
</style>
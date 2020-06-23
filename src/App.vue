<template>
  <div id="app">
    <!-- 头部组件 -->
    <my-header />
    <!-- 地图主题组件 -->
    <div class="main">
      <layer id="map"></layer>
    </div>
  </div>
</template>

<script>
import MyHeader from "./components/Header.vue";
import layer from "./map/layer.vue";
export default {
  name: "App",
  methods: {},
  data() {
    return {};
  },
  components: {
    MyHeader,
    layer
  },
};
</script>

<style lang="less">
html,
body {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
}

.main {
  position: absolute;
  top: 70px;
  bottom: 0;
  width: 100%;

  #map {
    width: 100%;
    height: 100%;
  }
}
</style>

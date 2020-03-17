
<template>
  <div class="page-container">
    <div class="page-body-abs-container">
      <div class="operate-general-body" id="app">
        <div class="aside-nav bounceInUp animated" id="aside-nav1" style="top: 100px;left:20px">
          <span class="aside-menu">基础热力图</span>
          <span class="menu-item menu-first" id="human">人群分布</span>
          <span class="menu-item menu-second" id="transport">车辆轨迹</span>
          <span class="menu-item menu-third" id="risk">风险系数</span>
        </div>

        <div class="aside-nav bounceInUp animated" id="aside-nav2" style="top: 280px;left:20px">
          <span class="aside-menu">风险模式</span>
          <span class="menu-item menu-first" id="slider">模式挖掘</span>
          <span class="menu-item menu-second">风险2</span>
          <span class="menu-item menu-third" id="rankList">排名</span>
        </div>

        <div class="aside-nav bounceInUp animated" id="aside-nav3" style="top: 460px;left:20px">
          <span class="aside-menu">规划管理</span>
          <span class="menu-item menu-first">规划1</span>
          <span class="menu-item menu-second">规划2</span>
          <span class="menu-item menu-third">规划3</span>
        </div>

        <div
          id="map"
          class="minemap-canvas-container minemap-interactive minemap-touch-drag-pan minemap-touch-zoom-rotate"
          style="z-index: 100;"
        ></div>
        <!-- <div id="mapSide" class="minemap-canvas-container minemap-interactive minemap-touch-drag-pan minemap-touch-zoom-rotate"
							 style="width: 250px; height: 180px; top: 500px; left: 1250px; z-index: 105;position: absolute; border:1px solid #084485;opacity: 0.8;">
        </div>-->
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  // data() {
  //   return {
  //     msg: "Welcome to Your Vue.js App"
  //   };
  // }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style  scoped>
@import '../../static/css/asidenav.css';
@import '../../static/css/commons.min.css';
@import '../../static/css/loading.css';
@import '../../static/css/minemap.css';
@import '../../static/css/operate.min.css';
</style>
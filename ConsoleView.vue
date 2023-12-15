<script setup>
import LeftSide from '@/components/console/LeftSide.vue'
import MainContents from '@/components/console/MainContents.vue'
import RightSide from '@/components/console/RightSide.vue'
import FloatingButton from '@/components/console/playlist_floating.vue'
</script>

<template>
  <div class="console-container">
    <div class="console-panel-i" id="panel_menu" style="width: 250px; left: 0; ">
      <LeftSide />
    </div>
    <div class="console-panel">
      <MainContents/>
    </div>
    <div class="console-panel-i" id="panel_playlist_side" style="width: 370px; right: 0;">
      <RightSide  />
    </div>
    <div class="scrollbar" id="panel_scrolbar" style="right: 0; width: 5px;">
      <ScrollBar  />
    </div>
  </div>
  
</template>

<style scoped>
.console-container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0px;
  padding: 0px;
  background: black;
}

.console-panel {
  display: flex;
  position: sticky;
  flex-direction: column;
  justify-content: space-between;
  width: 100vw;
  height: 6000px;
  z-index: 999;
  overflow: auto;
}

.console-panel-i {
  display: flex;
  position: fixed;
  flex-direction: column;
  justify-content: space-between;
  width: 300px;
  height: 6000px;
  backdrop-filter: blur(30px);
  border-right: 2px solid rgb(255, 255, 255, 0.1);
  background-color: rgba(29, 29, 29, 0.671);
  z-index: 999;
}
</style>

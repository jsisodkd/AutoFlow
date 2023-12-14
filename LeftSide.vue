<script setup>
import Swiper from 'vue-awesome-swiper'
import 'swiper/swiper-bundle.css'
</script>

<template>
  <div class="left-side">
    <div class="logo-box">
      <img class="logo" src="@/assets/images/UVATALIElogo.png">
      <span>UV-AUTOFLOW</span>
    </div>
    <div class="menu">
      <div class="menu-item" href="./uvmusicai/playlist.html">
        <span class="menu-emoji" >📚</span>플레이리스트
      </div>
      <div class="menu-item" onclick="location.href='./uvmusicai/playlist.html'">
        <span class="menu-emoji">⭐</span>좋아요 누른 음악
      </div>
      <div class="menu-item" onclick="location.href='./uvmusicai/playlist.html'">
        <span class="menu-emoji">🔍</span>최근 검색한 음악
      </div>
      <div class="log" onclick="location.href='./uvmusicai/playlist.html'">
        <p class="logout">🔍로그아웃</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.left-side {
    width: 200px;
    padding: 30px;
    height: 6000px;
}

.logo-box {
    display: flex;
    align-items: center;
}

.logo-box span {
    margin-left: 10px;
    color: white;
    font-weight: bold;
}

.logo {
    width: 35px;
    height: 35px;
}

.menu {
    margin-top: 100px;
}

.menu-item {
    display: flex;
    align-items: center;
    height: 50px;
    color: rgb(255, 255, 255);
    user-select: none;
    cursor: pointer;
    font-size: 15px;
    font-weight: 900;
}

.menu-emoji {
    margin-right: 20px;
}

.log {
    display: flex;
    align-items: center;
    height: 50px;
    color: white;
    user-select: none;
    cursor: pointer;
    margin-right: 20px;
    margin-top: 570px;
    font-size: 17px;
    font-weight: 800;
}

.logout {
    color: white;
    margin-right: 20px;
}
</style>

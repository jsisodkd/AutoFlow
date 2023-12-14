<script setup>
import Swiper from 'vue-awesome-swiper'
import 'swiper/swiper-bundle.css'

//엔터키 키다운 이벤트가 발생하면 검색 호출
function onKeydown(e)
{
  const key = e.key || e.keyCode;
  if (key === 'Enter' || key === 13) Search();
}
function Search()
{
  //input 에서 키워드 가져와서 검색 ㄱㄱ
  alert("엔터기를 눌렀으니 여기서 검색하시면 됩니다")
}
</script>

<template>
  <div class="dashboard">
    <div class="top-text">
      <div class="arrow-down">
        <i class="fa-solid fa-arrow-down-long" style="color: #ffffff;"></i>
      </div>
      <div class="good-text">Good!</div>
      <div class="timer-text">Evening</div>
    </div>
    <div class="search-box">
      <input type="text" class="answerInput" placeholder="Search for song, artist, lymics.." v-on:keydown="onKeydown">
    </div>
    <div class="trend-container">
      <p>Trending Right Now</p>
      <div class="trend-box">
        <h4>01</h4>
        <img src="" alt="">
        <div class="music-explane">
          <h3>Millons</h3>
          <h5>Always Never</h5>
        </div>
        <div class="music-name">Always Never</div>
        <div class="hits">8,069,542</div>
        <div class="music-path">3:52</div>
      </div>
      <div class="trend-box-i">
        <h4>02</h4>
        <img src="" alt="">
        <div class="music-explane-i">
          <h3>Millons</h3>
          <h5>Always Never</h5>
        </div>
        <div class="music-name-i">Always Never</div>
        <div class="hits-i">8,069,542</div>
        <div class="music-path-i">3:52</div>
      </div>
      <div class="trend-box-ii">
        <h4>03</h4>
        <img src="" alt="">
        <div class="music-explane-ii">
          <h3>Millons</h3>
          <h5>Always Never</h5>
        </div>
        <div class="music-name-ii">Always Never</div>
        <div class="hits-ii">8,069,542</div>
        <div class="music-path-ii">3:52</div>
      </div>
    </div>
    <div class="pop-box">
      <p>POP</p>
      <div class="pop"></div>
    </div>
    <div class="hiphop-box">
      <p>Hip-Hop</p>
      <div class="hip-hop"></div>
    </div>
    <div class="jazz-box">
      <p>JAZZ</p>
      <div class="jazz"></div>
    </div>
    <div class="electronic-box">
      <p>Electronic</p>
      <div class="electronic"></div>
    </div>
    <div class="hit-txt"></div>
    <div class="header-line"></div>
    <div class="hit-container">
      <div class="hit">Hot Music Playlist</div>
      <div class="hit-box" onclick="location.href= './components/about.html'"></div>
      <div class="hit-box-s" onclick="location.href= './about.html'"></div>
      <div class="hit-box-v" onclick="location.href= './about.html'"></div>
      <div class="hit-box-t" onclick="location.href= './about.html'"></div>
      <div class="hit-box-w" onclick="location.href= './about.html'"></div>
      <div class="hit-box-y" onclick="location.href= './about.html'"></div>
      <div class="hit-box-z" onclick="location.href= './about.html'"></div>
      <div class="hit-box-a" onclick="location.href= './about.html'"></div>
      <div class="hit-box-b" onclick="location.href= './about.html'"></div>
      <div class="main-box"></div>
      <div class="main-box-i"></div>
      <div class="main-box-ii"></div>
      <div class="musicimg-box"></div>
      <div class="msexplane-txt"></div>
      <div class="get">Get more</div>
    </div>
    <div class="daily-container">
      <div class="daily">Daily</div>
      <div class="daily-box-s" onclick="location.href= './about.html'"></div>
      <div class="daily-box-v" onclick="location.href= './about.html'"></div>
      <div class="daily-box-t" onclick="location.href= './about.html'"></div>
      <div class="daily-box-w" onclick="location.href= './about.html'"></div>
      <div class="daily-box-y" onclick="location.href= './about.html'"></div>
      <div class="daily-box-z" onclick="location.href= './about.html'"></div>
      <div class="daily-box-a" onclick="location.href= './about.html'"></div>
      <div class="daily-box-b" onclick="location.href= './about.html'"></div>
      <div class="get-i">Get more</div>
    </div>
    <div class="advertise-box"></div>
    <div class="list-music">
      <p>나를 위한 데일리 믹스</p>
      <div class="mix-container">
        <div class="mix-box-s" onclick="location.href='test.html'">
          <img src="./7639160.jpg" onclick="location.href='test.html'">
          <p>너무나도 더운 요즘을<br>위한 음원 목록</p>
        </div>
        <div class="mix-box-v" onclick="location.href='test.html'">
          <img src="./5924229.jpg" onclick="location.href='test.html'">
          <p>너무나도 더운 요즘을<br>위한 음원 목록</p>
        </div>
        <div class="mix-box-t" onclick="location.href='test.html'">
          <img src="./emotion.jpg" onclick="location.href='test.html'">
          <p>너무나도 더운 요즘을<br>위한 음원 목록</p>
        </div>
        <div class="mix-box-w" onclick="location.href='test.html'">
          <img src="./emotion.jpg" onclick="location.href='test.html'">
          <p>너무나도 더운 요즘을<br>위한 음원 목록</p>
        </div>
        <div class="mix-box-y" onclick="location.href='test.html'">
          <img src="./emotion.jpg" onclick="location.href='test.html'">
          <p>너무나도 더운 요즘을<br>위한 음원 목록</p>
        </div>
        <div class="mix-box-z" onclick="location.href='test.html'">
          <img src="./emotion.jpg" onclick="location.href='test.html'">
          <p>너무나도 더운 요즘을<br>위한 음원 목록</p>
        </div>
      </div>
    </div>
    <div class="sra">
      <font-awesome-icon :icon="['fas', 'bell']" style="color: #d41cbc;" />
    </div>
    <div class="popular">
      <p>인기 오디오</p>
      <div class="popular-box-s">
        <img src="./emotion.jpg">
      </div>
      <div class="popular-box-v">
        <img src="./emotion.jpg">
      </div>
      <div class="popular-box-t">
        <img src="./emotion.jpg">
      </div>
      <div class="popular-box-w">
        <img src="./emotion.jpg">
      </div>
      <div class="popular-box-y">
        <img src="./emotion.jpg">
      </div>
      <div class="popular-box-z">
        <img src="./emotion.jpg">
      </div>
    </div>
    <div class="recent">
      <p>최근 재생 항목</p>
      <div class="recent-container">
        <div class="recent-box-s" href="./about.html">
          <img src="./emotion.jpg">
        </div>
        <div class="recent-box-v">
          <img src="./emotion.jpg">
        </div>
        <div class="recent-box-t">
          <img src="./emotion.jpg">
        </div>
        <div class="recent-box-w">
          <img src="./emotion.jpg">
        </div>
        <div class="recent-box-y">
          <img src="./emotion.jpg">
        </div>
        <div class="recent-box-z">
          <img src="./emotion.jpg">
        </div>
      </div>  
    </div>
    <div class="weekly">
      <div class="weekly-box" onclick="location.href='about.html'">
        <p>Weekly Playlist</p>
      </div>
    </div>
    <div class="monthly">
      <div class="monthly-box" onclick="location.href='test.html'">
        <p>Monthly Playlist</p>
      </div>
    </div>
    <div class="amazing">
      <div class="amazing-box" onclick="location.href='test.html'">
        <p>Amazing</p>\
        <font-awesome-icon :icon="['fas', 'bell']" style="color: #d41cbc;" />
      </div>
    </div>
    <div class="middle-line"></div>
    <div class="zip">
      <div class="zip-container">
        <div class="zip-box-s">
          <p>recommend<br>.zip</p>
          <div class="s-touch"></div>
        </div>
        <div class="zip-box-v">
          <p>recommend<br>.zip</p>
          <div class="v-touch"></div>
        </div>
        <div class="zip-box-t">
          <p>recommend<br>.zip</p>
          <div class="t-touch"></div>
        </div>
        <div class="zip-box-w">
          <p>recommend<br>.zip</p>
          <div class="w-touch"></div>
        </div>
        <div class="zip-box-y">
          <p>recommend<br>.zip</p>
          <div class="y-touch"></div>
        </div>
        <div class="zip-box-z">
          <p>recommend<br>.zip</p>
          <div class="z-touch"></div>
      </div>
      </div>
    </div>
    <div class="category">
      <div class="category-container">
        <p>Categoties</p>
        <div class="category-box-s"></div>
        <div class="category-box-v"></div>
        <div class="category-box-t"></div>
        <div class="category-box-w"></div>
        <div class="category-box-y"></div>
        <div class="category-box-z"></div>
        <div class="category-box-a"></div>
        <div class="category-box-b"></div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.dashboard {
  margin-left: 300px;
  width: 200px;
  padding: 30px;
  height: 5000px;

  position: relative;
  top: 155px;
}

.logo-box span {
  margin-left: 10px;
  color: white;
  font-weight: bold;
}

.good-text{
  position: relative;
  width: 1000px;
  font-size: 50px;
  font-weight: 600;
  color: #4A00E0;
  top: 1523px;
}

.timer-text {
  position: relative;
  font-size: 38px;
  font-weight: 700;
  width: 500px;
  top: 1515px;
  margin-left: 28px;
  font-size: 70px;
  letter-spacing: 10px;
  background: linear-gradient(to right, #4A00E0, #8E2DE2);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  transition: all 0.5s;
}

.answerInput {
  position: relative;
  align-items: center;
  top: -320px;
  left: 10px;
  width: 850px;
  height: 15px;
  padding: 15px;
  margin-right: 50px;
  border-radius: 30px;
  border: none;
  background-color: #363636e3;
  font-size: 16px;
  color: #c7c0c0e5;
  outline: none;
  box-shadow: 0px 3px 15px rgba(0, 0, 0, 0.1);
  transition: box-shadow 0.3s ease;
}

.answerInput:focus {
  box-shadow: 0px 5px 15px rgba(201, 200, 200, 0.2);
}

.answerInput::placeholder {
  color: #999999;
}

.answerInput + .answerInput {
  margin-top: 10px;
}

.answerInput::before {
  content: '';
  display: block;
  position: absolute;
  top: 50%;
  left: 20px;
  transform: translateY(-50%);
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background-color: #555555;
  opacity: 0;
  transition: opacity 0.3s ease;
}

.trend-container {
  position: absolute;
  top: 150px;
  left: 30px;
}

.trend-container p{
  position: absolute;
  width: 200px;
  color: white;
  font-size: 19px;
  font-weight: 700;
}

.trend-box {
  position: absolute;
  top: 60px;
  width: 870px;
  height: 70px;
  background-color: rgba(24, 23, 23, 0.466);
  border-radius: 10px;
}

.trend-box h4 {
  position: absolute;
  top: -5px;
  left: 30px;
  font-size: 20px;
  font-weight: 800;
  color: rgb(83, 82, 82);
}

.music-explane h3 {
  position: absolute;
  top: -13px;
  left: 160px;
  font-size: 21px;
  font-weight: 800;
  color: rgb(223, 220, 220);
}

.music-explane h5 {
  position: absolute;
  top: 17px;
  left: 160px;
  font-size: 13px;
  font-weight: 800;
  color: rgb(83, 82, 82);
}

.music-name {
  position: absolute;
  top: 25px;
  left: 330px;
  font-size: 14px;
  font-weight: 800;
  color: rgb(187, 185, 185);
}

.hits {
  position: absolute;
  top: 25px;
  left: 490px;
  font-size: 14px;
  font-weight: 800;
  color: rgb(187, 185, 185);
}

.music-path {
  position: absolute;
  top: 25px;
  left: 650px;
  font-size: 14px;
  font-weight: 800;
  color: rgb(187, 185, 185);
}

.trend-box-i {
  position: absolute;
  top: 140px;
  width: 870px;
  height: 70px;
  background-color: rgba(24, 23, 23, 0.466);
  border-radius: 12px;
}

.trend-box-i h4 {
  position: absolute;
  top: -5px;
  left: 30px;
  font-size: 20px;
  font-weight: 800;
  color: rgb(83, 82, 82);
}

.music-explane-i h3 {
  position: absolute;
  top: -13px;
  left: 160px;
  font-size: 21px;
  font-weight: 800;
  color: rgb(223, 220, 220);
}

.music-explane-i h5 {
  position: absolute;
  top: 17px;
  left: 160px;
  font-size: 13px;
  font-weight: 800;
  color: rgb(83, 82, 82);
}

.music-name-i {
  position: absolute;
  top: 25px;
  left: 330px;
  font-size: 14px;
  font-weight: 800;
  color: rgb(187, 185, 185);
}

.hits-i {
  position: absolute;
  top: 25px;
  left: 490px;
  font-size: 14px;
  font-weight: 800;
  color: rgb(187, 185, 185);
}

.music-path-i {
  position: absolute;
  top: 25px;
  left: 650px;
  font-size: 14px;
  font-weight: 800;
  color: rgb(187, 185, 185);
}

.trend-box-ii {
  position: absolute;
  top: 220px;
  width: 870px;
  height: 70px;
  background-color: rgba(24, 23, 23, 0.466);
  border-radius: 12px;
}

.trend-box-ii h4 {
  position: absolute;
  top: -5px;
  left: 30px;
  font-size: 20px;
  font-weight: 800;
  color: rgb(83, 82, 82);
}

.music-explane-ii h3 {
  position: absolute;
  top: -13px;
  left: 160px;
  font-size: 21px;
  font-weight: 800;
  color: rgb(223, 220, 220);
}

.music-explane-ii h5 {
  position: absolute;
  top: 17px;
  left: 160px;
  font-size: 13px;
  font-weight: 800;
  color: rgb(83, 82, 82);
}

.music-name-ii {
  position: absolute;
  top: 25px;
  left: 330px;
  font-size: 14px;
  font-weight: 800;
  color: rgb(187, 185, 185);
}

.hits-ii {
  position: absolute;
  top: 25px;
  left: 490px;
  font-size: 14px;
  font-weight: 800;
  color: rgb(187, 185, 185);
}

.music-path-ii {
  position: absolute;
  top: 25px;
  left: 650px;
  font-size: 14px;
  font-weight: 800;
  color: rgb(187, 185, 185);
}

.pop-box {
  position: absolute;
  top: -50px;
  bottom: -470px;
  left: 20px;
  width: 256px;
  height: 160px;
  background: #FC466B;  /* fallback for old browsers */
  background: linear-gradient(to left, #3e0355, #150455); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  border-radius: 15px;
  font-size: 23px;
  color: white;
}

.pop-box p{
  position: absolute;
  top: 5px;
  left: 30px;
  color: white;
}

.pop {
  position: absolute;
  top: 87px;
  left: 33px;
  width: 190px;
  height: 60px;
  background-color: rgba(255, 255, 255, 0.37);
  border-radius: 15px;
}

.hiphop-box {
  position: absolute;
  top: -50px;
  bottom: -470px;
  left: 300px;
  width: 256px;
  height: 160px;
  background: #00F260;  /* fallback for old browsers */
  background: linear-gradient(to right, #013812, #012533); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  border-radius: 15px;
  font-size: 23px;
  color: white;
}

.hiphop-box p{
  position: absolute;
  top: 5px;
  left: 30px;
  color: white;
}

.hip-hop {
  position: absolute;
  top: 87px;
  left: 33px;
  width: 190px;
  height: 60px;
  background-color: rgba(255, 255, 255, 0.37);
  border-radius: 15px;
  z-index: 999;
}

.jazz-box {
  position: absolute;
  top: -50px;
  bottom: -470px;
  left: 580px;
  width: 256px;
  height: 160px;
  background: #c0392b;  /* fallback for old browsers */
  background: linear-gradient(to bottom, #0e2747, #080147); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  border-radius: 15px;
  font-size: 23px;
  color: white;
}

.jazz-box p{
  position: absolute;
  top: 5px;
  left: 30px;
  color: white;
}

.jazz {
  position: absolute;
  top: 87px;
  left: 33px;
  width: 190px;
  height: 60px;
  background-color: rgba(255, 255, 255, 0.37);
  border-radius: 15px;
  z-index: 999;
}

.jazz-box img {
  position: absolute;
  top: 100px;
  left: 170px;
  cursor: pointer;
}

.electronic-box {
  position: absolute;
  top: -50px;
  bottom: -470px;
  left: 860px;
  width: 256px;
  height: 160px;
  background: #009FFF;  /* fallback for old browsers */
  background: linear-gradient(to right, #032d35, #063350); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  border-radius: 15px;
  font-size: 23px;
  color: white;
}

.electronic {
  position: absolute;
  top: 87px;
  left: 33px;
  width: 190px;
  height: 60px;
  background-color: rgba(255, 255, 255, 0.37);
  border-radius: 15px;
  z-index: 999;
}

.electronic-box p {
  position: absolute;
  top: 5px;
  left: 30px;
  color: white;
}

.hit {
  position: relative;
  top: 80px;
  width: 250px;
  color: #ffffffa8;
  margin-left: 40px;
  font-size: 25px;
}

.header-line {
  width: 100%;
  height: 1px;
  background: radial-gradient(circle at center, rgb(255, 255, 255) 100%);
}

.hit-container {
  position: absolute;
  top: 430px;
}

.daily-container {
  position: absolute;
  top: 340px;
  z-index: 99;
}

.hit-box {
  position: relative;
  top: 110px;
  margin-left: 40px;
  width: 90px;
  height: 90px;
  border-radius: 20px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: #355C7D;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #C06C84, #6C5B7B, #355C7D);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #C06C84, #6C5B7B, #355C7D); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.hit-box:hover::after {
  background-color: rgb(54, 54, 54);
}

.hit-box-s {
  position: relative;
  top: 20px;
  margin-left: 160px;
  width: 90px;
  height: 90px;
  border-radius: 20px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: #355C7D;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #C06C84, #6C5B7B, #355C7D);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #C06C84, #6C5B7B, #355C7D); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.hit-box-v {
  position: relative;
  top: -70px;
  margin-left: 280px;
  width: 90px;
  height: 90px;
  border-radius: 20px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: #355C7D;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #C06C84, #6C5B7B, #355C7D);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #C06C84, #6C5B7B, #355C7D); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.hit-box-t {
  position: relative;
  top: -160px;
  margin-left: 400px;
  width: 90px;
  height: 90px;
  border-radius: 20px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: #355C7D;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #C06C84, #6C5B7B, #355C7D);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #C06C84, #6C5B7B, #355C7D); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.hit-box-w {
  position: relative;
  top: -250px;
  margin-left: 520px;
  width: 90px;
  height: 90px;
  border-radius: 20px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: #355C7D;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #C06C84, #6C5B7B, #355C7D);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #C06C84, #6C5B7B, #355C7D); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.hit-box-z {
  position: relative;
  top: -340px;
  margin-left: 640px;
  width: 90px;
  height: 90px;
  border-radius: 20px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: #355C7D;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #C06C84, #6C5B7B, #355C7D);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #C06C84, #6C5B7B, #355C7D); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.get {
  position: relative;
  top: -320px;
  color: white;
  width: 100px;
  font-size: 17px;
  font-weight: 100;
  margin-left: 40px;
  z-index: 999;
  cursor: pointer;
}

.daily-box-s {
  position: relative;
  top: 563px;
  margin-left: 40px;
  width: 90px;
  height: 90px;
  border-radius: 20px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: #355C7D;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #C06C84, #6C5B7B, #355C7D);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #C06C84, #6C5B7B, #355C7D); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.daily-box-t {
  position: relative;
  top: 383px;
  margin-left: 160px;
  width: 90px;
  height: 90px;
  border-radius: 20px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: #355C7D;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #C06C84, #6C5B7B, #355C7D);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #C06C84, #6C5B7B, #355C7D); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.daily-box-v {
  position: relative;
  top: 472px;
  margin-left: 280px;
  width: 90px;
  height: 90px;
  border-radius: 20px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: #355C7D;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #C06C84, #6C5B7B, #355C7D);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #C06C84, #6C5B7B, #355C7D); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.daily-box-w {
  position: relative;
  top: 292px;
  margin-left: 400px;
  width: 90px;
  height: 90px;
  border-radius: 20px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: #355C7D;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #C06C84, #6C5B7B, #355C7D);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #C06C84, #6C5B7B, #355C7D); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.daily-box-y {
  position: relative;
  top: 202px;
  margin-left: 520px;
  width: 90px;
  height: 90px;
  border-radius: 20px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: #355C7D;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #C06C84, #6C5B7B, #355C7D);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #C06C84, #6C5B7B, #355C7D); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.daily-box-z {
  position: relative;
  top: 112px;
  margin-left: 640px;
  width: 90px;
  height: 90px;
  border-radius: 20px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: #355C7D;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #C06C84, #6C5B7B, #355C7D);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #C06C84, #6C5B7B, #355C7D); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.daily {
  position: absolute;
  top: 500px;
  width: 250px;
  color: #ffffffa8;
  margin-left: 40px;
  font-size: 25px;
}

.daily-container {
  position: absolute;
  top: 330px;
}

.get-i {
  position: absolute;
  top: 671px;
  color: white;
  width: 100px;
  font-size: 17px;
  font-weight: 100;
  margin-left: 40px;
  cursor: pointer;
}

.advertise-box {
  position: relative;
  top: 900px;
  left: 10px;
  align-items: center;
  justify-content: center;
  width: 1100px;
  height: 250px;
  background-color: white;
  border: 3px solid #6507bd;
  border-radius: 18px;
  background: url(./baner.png);
}

.advertise-box p {
  margin-top: 70px;
  text-align: center;
  justify-content: center;
  font-size: 60px;
  font-family: sans-serif;
  font-weight: 800;
  color: black;
}

.list-music p{
  position: relative;
  top: 1250px;
  color: white;
  font-family: sans-serif;
  width: 300px;
  font-weight: 900;
  font-size: 23px;
}

.mix-box-s {
  position: relative;
  top: 1270px;
  margin-left: 20px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
  cursor: pointer;
}

.mix-box-s p {
  position: relative;
  top: 12px;
  left: -70px;
  font-size: 12px;
  font-family: sans-serif;
  text-align: center;
  z-index: 999;
  color: rgb(182, 179, 179);
}

.mix-box-s img {
  position: relative;
  top: 17px;
  left: 20px;
  width: 120px;
  height: 110px;
  border-radius: 7px;
  z-index: 0;
  opacity: 1;
}

.mix-box-s:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.mix-box-s img:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.mix-box-v {
  position: relative;
  top: 1070px;
  margin-left: 220px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
  cursor: pointer;
}

.mix-box-v p {
  position: relative;
  top: 12px;
  left: -70px;
  font-size: 12px;
  font-family: sans-serif;
  text-align: center;
  z-index: 999;
  color: rgb(182, 179, 179);
}

.mix-box-v img {
  position: relative;
  top: 17px;
  left: 20px;
  width: 120px;
  height: 110px;
  border-radius: 7px;
  z-index: 0;
}

.mix-box-v:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.mix-box-v img:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  opacity: 5;
  transition: all 1s ease-out;
}

.mix-box-t {
  position: relative;
  top: 870px;
  margin-left: 420px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
  cursor: pointer;
}

.mix-box-t p {
  position: relative;
  top: 12px;
  left: -70px;
  font-size: 12px;
  font-family: sans-serif;
  text-align: center;
  z-index: 999;
  color: rgb(182, 179, 179);
}

.mix-box-t img {
  position: relative;
  top: 17px;
  left: 20px;
  width: 120px;
  height: 110px;
  border-radius: 7px;
  z-index: 0;
}

.mix-box-t:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.mix-box-t img:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
}

.mix-box-w {
  position: relative;
  top: 670px;
  margin-left: 620px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
  cursor: pointer;
}

.mix-box-w p {
  position: relative;
  top: 12px;
  left: -70px;
  font-size: 12px;
  font-family: sans-serif;
  text-align: center;
  z-index: 999;
  color: rgb(182, 179, 179);
}

.mix-box-w img {
  position: relative;
  top: 17px;
  left: 20px;
  width: 120px;
  height: 110px;
  border-radius: 7px;
  z-index: 0;
}

.mix-box-w:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.mix-box-w img:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  opacity: 5;
  transition: all 1s ease-out;
}

.mix-box-y {
  position: relative;
  top: 470px;
  margin-left: 820px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
  cursor: pointer;
}

.mix-box-y p {
  position: relative;
  top: 12px;
  left: -70px;
  font-size: 12px;
  font-family: sans-serif;
  text-align: center;
  z-index: 999;
  color: rgb(182, 179, 179);
}

.mix-box-y img {
  position: relative;
  top: 17px;
  left: 20px;
  width: 120px;
  height: 110px;
  border-radius: 7px;
  z-index: 0;
}

.mix-box-y:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.mix-box-y img:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  opacity: 5;
  transition: all 1s ease-out;
}

.mix-box-z {
  position: relative;
  top: 270px;
  margin-left: 1020px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
  cursor: pointer;
}

.mix-box-z p {
  position: relative;
  top: 12px;
  left: -70px;
  font-size: 12px;
  font-family: sans-serif;
  text-align: center;
  z-index: 999;
  color: rgb(182, 179, 179);
}

.mix-box-z img {
  position: relative;
  top: 17px;
  left: 20px;
  width: 120px;
  height: 110px;
  border-radius: 7px;
  z-index: 0;
}

.mix-box-z:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.mix-box-z img:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  opacity: 5;
  transition: all 1s ease-out;
}

.popular p {
  position: relative;
  top: 352px;
  color: white;
  font-family: sans-serif;
  width: 300px;
  font-weight: 900;
  font-size: 23px;
}

.popular-box-s {
  position: relative;
  top: 370px;
  margin-left: 20px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
}

.popular-box-s img {
  position: relative;
  top: 17px;
  left: 15px;
  width: 130px;
  height: 120px;
  border-radius: 7px;
  border: inset 4px solid rgba(0, 0, 0, 0.);
  z-index: 0;
}

.popular-box-s:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.popular-box-v {
  position: relative;
  top: 170px;
  margin-left: 220px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
}

.popular-box-v img {
  position: relative;
  top: 17px;
  left: 15px;
  width: 130px;
  height: 120px;
  border-radius: 7px;
  border: inset 4px solid rgba(0, 0, 0, 0.);
  z-index: 0;
}

.popular-box-v:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.popular-box-t {
  position: relative;
  top: -30px;
  margin-left: 420px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
}

.popular-box-t img {
  position: relative;
  top: 17px;
  left: 15px;
  width: 130px;
  height: 120px;
  border-radius: 7px;
  border: inset 4px solid rgba(0, 0, 0, 0.);
  z-index: 0;
}

.popular-box-t:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.popular-box-w {
  position: relative;
  top: -230px;
  margin-left: 620px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
}

.popular-box-w img {
  position: relative;
  top: 17px;
  left: 15px;
  width: 130px;
  height: 120px;
  border-radius: 7px;
  border: inset 4px solid rgba(0, 0, 0, 0.);
  z-index: 0;
}

.popular-box-w:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.popular-box-y {
  position: relative;
  top: -430px;
  margin-left: 820px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
}

.popular-box-y img {
  position: relative;
  top: 17px;
  left: 15px;
  width: 130px;
  height: 120px;
  border-radius: 7px;
  border: inset 4px solid rgba(0, 0, 0, 0.);
  z-index: 0;
}

.popular-box-y:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.popular-box-z {
  position: relative;
  top: -630px;
  margin-left: 1020px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
}

.popular-box-z img {
  position: relative;
  top: 17px;
  left: 15px;
  width: 130px;
  height: 120px;
  border-radius: 7px;
  border: inset 4px solid rgba(0, 0, 0, 0.);
  z-index: 0;
}

.popular-box-z:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.recent p {
  position: relative;
  top: -550px;
  color: white;
  font-family: sans-serif;
  width: 300px;
  font-weight: 900;
  font-size: 23px;
}

.recent-container {
  position: relative;
  top: -900px;
}

.recent-box-s {
  position: relative;
  top: 370px;
  margin-left: 20px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
}

.recent-box-s img {
  position: relative;
  top: 17px;
  left: 15px;
  width: 130px;
  height: 120px;
  border-radius: 7px;
  border: inset 4px solid rgba(0, 0, 0, 0.);
  z-index: 0;
}

.recent-box-s:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.recent-box-v {
  position: relative;
  top: 170px;
  margin-left: 220px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
}

.recent-box-v img {
  position: relative;
  top: 17px;
  left: 15px;
  width: 130px;
  height: 120px;
  border-radius: 7px;
  border: inset 4px solid rgba(0, 0, 0, 0.);
  z-index: 0;
}

.recent-box-v:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.recent-box-t {
  position: relative;
  top: -30px;
  margin-left: 420px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
}

.recent-box-t img {
  position: relative;
  top: 17px;
  left: 15px;
  width: 130px;
  height: 120px;
  border-radius: 7px;
  border: inset 4px solid rgba(0, 0, 0, 0.);
  z-index: 0;
}

.recent-box-t:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.recent-box-w {
  position: relative;
  top: -230px;
  margin-left: 620px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
}

.recent-box-w img {
  position: relative;
  top: 17px;
  left: 15px;
  width: 130px;
  height: 120px;
  border-radius: 7px;
  border: inset 4px solid rgba(0, 0, 0, 0.);
  z-index: 0;
}

.recent-box-w:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.recent-box-y {
  position: relative;
  top: -430px;
  margin-left: 820px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
}

.recent-box-y img {
  position: relative;
  top: 17px;
  left: 15px;
  width: 130px;
  height: 120px;
  border-radius: 7px;
  border: inset 4px solid rgba(0, 0, 0, 0.);
  z-index: 0;
}

.recent-box-y:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.recent-box-z {
  position: relative;
  top: -630px;
  margin-left: 1020px;
  width: 160px;
  height: 200px;
  border-radius: 15px;
  box-shadow: inset 2px 4px 5px rgba(0, 0, 0, 0.404);
  background: rgb(43, 41, 41);
}

.recent-box-z img {
  position: relative;
  top: 17px;
  left: 15px;
  width: 130px;
  height: 120px;
  border-radius: 7px;
  border: inset 4px solid rgba(0, 0, 0, 0.);
  z-index: 0;
}

.recent-box-z:hover {
  background-color: rgb(73, 71, 71);
  transform: translateY(0);
  transition: all 0.5s ease-out;
}

.weekly-box {
  position: relative;
  top: -1340px;
  left: 70px;
  width: 300px;
  height: 160px;
  border: 4px solid rgb(49, 48, 48);
  border-radius: 8px;
  background: linear-gradient(to right, #3177b4, #5321af);
  cursor: pointer;
}

.weekly-box:hover {
  background-color: rgb(53, 52, 52);
  opacity: 0.5;
  transition: all 0.3s ease-out;
}

.weekly-box p {
  position: relative;
  top: -10px;
  left: 20px;
  font-family: sans-serif;
  font-weight: 400;
  font-size: 23px;
  z-index: 999;
  color: #ffffffa4;
}

.monthly-box {
  position: relative;
  top: -1508px;
  left: 430px;
  width: 300px;
  height: 160px;
  border: 4px solid rgb(49, 48, 48);
  border-radius: 8px;
  background: linear-gradient(to right, #185479, #282a96);
  cursor: pointer;
}

.monthly-box:hover {
  background-color: rgb(53, 52, 52);
  opacity: 0.5;
  transition: all 0.3s ease-out;
}

.monthly-box p {
  position: relative;
  top: -10px;
  left: 20px;
  font-family: sans-serif;
  font-weight: 400;
  font-size: 23px;
  z-index: 999;
  color: #ffffffa4;
}

.amazing-box {
  position: relative;
  top: -1675px;
  left: 790px;
  width: 300px;
  height: 160px;
  border: 4px solid rgb(49, 48, 48);
  border-radius: 8px;
  background: linear-gradient(to left, #97598b, #424296);
  cursor: pointer;
}

.amazing-box:hover {
  background-color: rgb(53, 52, 52);
  opacity: 0.5;
  transition: all 0.3s ease-out;
}

.amazing-box p {
  position: relative;
  top: -10px;
  left: 20px;
  font-family: sans-serif;
  font-weight: 400;
  font-size: 23px;
  z-index: 999;
  color: #ffffffa4;
}

.middle-line {
  position: relative;
  top: -1530px;
  left: 230px;
  width: 690px;
  height: 1px;
  background-color: #ffffff;
}

.zip-container {
  position: relative;
  top: -0px;
  left: 30px;
}

.zip-box-s {
  position: relative;
  top: -1500px;
  left: 20px;
  width: 120px;
  height: 120px;
  background: linear-gradient(to right, #69355e, #34347a);
  border-radius: 6px;
  cursor: pointer;
}

.zip-box-s:hover {
  opacity: 0.5;
  transition: all 0.3s ease-out;
}

.zip-box-s p {
  position: relative;
  top: 10px;
  left: 10px;
  font-family: sans-serif;
  font-weight: 600;
  font-size: 17px;
  color: rgb(238, 231, 231);
}

.zip-box-v {
  position: relative;
  top: -1637px;
  left: 210px;
  width: 120px;
  height: 120px;
  background: linear-gradient(to right, #21486d, #523572);
  border-radius: 6px;
  cursor: pointer;
}

.zip-box-v:hover {
  opacity: 0.5;
  transition: all 0.3s ease-out;
}

.zip-box-v p {
  position: relative;
  top: 10px;
  left: 10px;
  font-family: sans-serif;
  font-weight: 600;
  font-size: 17px;
  color: rgb(255, 255, 255);
}

.zip-box-t {
  position: relative;
  top: -1774px;
  left: 400px;
  width: 120px;
  height: 120px;
  background: linear-gradient(to right, #335d77, #2a316b);
  border-radius: 6px;
  cursor: pointer;
}

.zip-box-t:hover {
  opacity: 0.5;
  transition: all 0.3s ease-out;
}

.zip-box-t p {
  position: relative;
  top: 10px;
  left: 10px;
  font-family: sans-serif;
  font-weight: 600;
  font-size: 17px;
  color: rgb(255, 255, 255);
}

.zip-box-w {
  position: relative;
  top: -1910px;
  left: 590px;
  width: 120px;
  height: 120px;
  background: linear-gradient(to right, #11315f, #1e6169);
  border-radius: 6px;
  cursor: pointer;
}

.zip-box-w:hover {
  opacity: 0.5;
  transition: all 0.3s ease-out;
}

.zip-box-w p {
  position: relative;
  top: 10px;
  left: 10px;
  font-family: sans-serif;
  font-weight: 600;
  font-size: 17px;
  color: rgb(255, 255, 255);
}

.zip-box-y {
  position: relative;
  top: -2047px;
  left: 780px;
  width: 120px;
  height: 120px;
  background: linear-gradient(to right, #336959, #30456e);
  border-radius: 6px;
  cursor: pointer;
}

.zip-box-y:hover {
  opacity: 0.5;
  transition: all 0.3s ease-out;
}

.zip-box-y p {
  position: relative;
  top: 10px;
  left: 10px;
  font-family: sans-serif;
  font-weight: 600;
  font-size: 17px;
  color: rgb(255, 255, 255);
}

.zip-box-z {
  position: relative;
  top: -2185px;
  left: 970px;
  width: 120px;
  height: 120px;
  background: linear-gradient(to right, #284758, #64306e);
  border-radius: 6px;
  cursor: pointer;
}

.zip-box-z:hover {
  opacity: 0.5;
  transition: all 0.3s ease-out;
}

.zip-box-z p {
  position: relative;
  top: 10px;
  left: 10px;
  font-family: sans-serif;
  font-weight: 600;
  font-size: 17px;
  color: rgb(255, 255, 255);
}

.category-container {
  position: relative;
  top: -100px;
}

.category p {
  position: relative;
  top: -1980px;
  left: 40px;
  font-size: 35px;
  font-family: sans-serif;
  font-weight: 700;
  color: white;
}

.category-box-s {
  position: relative;
  top: -1980px;
  left: 50px;
  width: 240px;
  height: 90px;
  background-color: rgb(255, 255, 255);
  border-radius: 7px;
}

.category-box-v {
  position: relative;
  top: -2070px;
  left: 320px;
  width: 240px;
  height: 90px;
  background-color: rgb(255, 255, 255);
  border-radius: 7px;
}

.category-box-t {
  position: relative;
  top: -2160px;
  left: 590px;
  width: 240px;
  height: 90px;
  background-color: rgb(255, 255, 255);
  border-radius: 7px;
}
</style>

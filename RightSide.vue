<script setup>
import LeftSide from '@/components/console/LeftSide.vue'
import MainContents from '@/components/console/MainContents.vue'
import RightSide from '@/components/console/RightSide.vue'
import FloatingButton from '@/components/console/playlist_floating.vue'
</script>

<template>
    <div class="right-side">
        <div class="playlist-container">
            <div class="top-content">
                <p>NEXT ON PLAYLIST CHART</p>
            </div>
            <div class="music-box">
                <div class="music-name">
                    <p>Natually</p>
                </div>
                <div class="artist">
                    <p>Tinashe</p>
                </div>
            </div>
            <div class="music-box">
                <div class="music-name">
                    <p>Natually</p>
                </div>
                <div class="artist">
                    <p>Tinashe</p>
                </div>
            </div>
            <div class="music-box">
                <div class="music-name">
                    <p>Natually</p>
                </div>
                <div class="artist">
                    <p>Tinashe</p>
                </div>
            </div>
            <div class="music-box">
                <div class="music-name">
                    <p>Natually</p>
                </div>
                <div class="artist">
                    <p>Tinashe</p>
                </div>
            </div>
            <div class="music-box">
                <div class="music-name">
                    <p>Natually</p>
                </div>
                <div class="artist">
                    <p>Tinashe</p>
                </div>
            </div>
            <div class="music-box">
                <div class="music-name">
                    <p>Natually</p>
                </div>
                <div class="artist">
                    <p>Tinashe</p>
                </div>
            </div>
        </div>
        <div class="sound-bar">
            <div class="music-img"></div>
            <div class="music-name1" onclick="location.href= './index.html'">
                <p>Natually</p>
            </div>
            <div class="artist1">
                <p>Tinashe</p>
            </div>
        </div>
        <div class="loop">
            <img src="./loop.png">
        </div>
        <div class="love">
            <img src="./love.png">
        </div>
        <div class="play-button">
            <img src="./play-button.png">
        </div>
        <div class="fast-forward">
            <img src="">
        </div>
    </div>
</template>

<style scoped>
.right-side {
    position: fixed;
}
.playlist-container {
    position: relative;
    top: 150px;
    padding: 30px;
}

.top-content {
    position: relative;
    top: -96px;
}

.top-content p {
    position: relative;
    color: rgb(211, 205, 205);
    font-weight: 900;
    font-size: 17.5px;
}

.music-box {
    position: relative;
    top: -90px;
    width: 60px;
    height: 60px;
    border-radius: 5px;
    background: #355C7D;  /* fallback for old browsers */
    background: -webkit-linear-gradient(to right, #C06C84, #6C5B7B, #355C7D);  /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(to right, #C06C84, #6C5B7B, #355C7D); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.music-name {
    position: relative;
    top: 10px;
    left: 84px;
}

.music-name p {
    position: relative;
    color: rgba(255, 255, 255, 0.774);
    font-weight: 800;
}

.artist {
    position: relative;
    top: -3px;
    left: 84px;
}

.artist p {
    position: relative;
    color: rgba(255, 255, 255, 0.486);
    font-size: 15px;
}

.sound-bar {
    display: flex;
    position: relative;
    top: 250px;
    left: 65%;
    transform: translate(-50%, -50%);
    width: 280px;
    height: 270px;
    border-radius: 18px;
    background: #3E5151;  /* fallback for old browsers */
    background: -webkit-linear-gradient(to right, #DECBA4, #3E5151);  /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(to top, #2b244e, #3E5151); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.music-name1 {
    position: relative;
    width: 210px;
    height: 120px;
    top: 185px;
    left: 50%;
    transform: translate(-50%, -50%);
    border-radius: 10px;
    background-color: rgba(0, 0, 0, 0.247);
}

.music-name1 p {
    position: relative;
    left: 27px;
    font-weight: 800;
    color: rgba(255, 255, 255, 0.774);
    z-index: 999;
    cursor: default;
}

.artist1 p {
    position: relative;
    top: 147px;
    right: 142px;
    color: rgba(255, 255, 255, 0.486);
    font-size: 15px;
    z-index: 999;
    cursor: pointer;
}

.loop img {
    top: 825px;
    left: 203px;
    width: 22px;
    height: 22px;
    position: absolute;
}

.love img {
    top: 825px;
    left: 239px;
    width: 22px;
    height: 22px;
    position: absolute;
}

.play-button img {
    top: 873px;
    left: 170px;
    width: 30px;
    height: 30px;
    position: absolute; 
}
</style>
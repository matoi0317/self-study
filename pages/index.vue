<template>
  <div>
    <div class="main-image">
      <img src="~/assets/main.jpg" />
      <div class="hero-content">
        ガリ勉自習室
      </div>
    </div>
    <div class="join">
      <a href="https://zoom.us/j/95721268706?pwd=VGcvV3J2ZHhBbEFNSFJaRFhnUzNoQT09" class="button is-primary is-fullwidth">
        ガリ勉自習室に参加する
      </a>
      <div class="help-text">ZOOMが自動的に開きます</div>
    </div>
    <div class="rules">
      <ul>
        <div class="a"><li><font color="red">・自習室のURLは09:50に配布します</font></li></div>
        <div class="b"><li>・自習室は<font color="red">月〜金に開放しています</font></li></div>
        <div class="c"><li><font color="red">・解放時間は10:00 ~ 17:00です</font></li></div>
        <div class="d"><li><font color="red">・自習室の様子をYouTubeにてLive配信しています</font></li></div>
        <li>・入室したらすぐに<font color="red">ミュート(消音)</font>にしてください</li>
        <li>・長時間退出する場合は<font color="red">挨拶をしてから</font>退出してください</li>
        <li>・なるべく手元を映してください</li>
        <li>・勉強の教え合い等話し合いがしたい場合は個別ルームを作るのでルーム長に声をかけてください</li>
        <li>・顔が移りそうな人は、プライバシーを守るために<font color="red">マスクをする</font>等対策をしてください</li>
        <li>・<font color="red">休憩時間のチャットは禁止です</font></li>
        <li>・プログラミングでも参加可能！</li>
        <li>・何歳でも参加可能なので、みんなで勉強しましょう！</li>
      </ul>
    </div>
    <div class="download">
      <h3>ZOOMのダウンロードはこちら(iphone)</h3>
      <a href="https://apps.apple.com/jp/app/zoom-cloud-meetings/id546505307" class="button is-primary is-fullwifth">
        ZOOMをダウンロード
        </a>
    </div>
    <div class="download-android">
      <h3>ZOOMのダウンロードはこちら(android)</h3>
      <a href="https://play.google.com/store/apps/details?id=us.zoom.videomeetings&hl=ja" class="button is-primary is-fullwifth">
        ZOOMをダウンロード
        </a>
    </div>
  </div>
</template>
<script>
export default {}
</script>
<style scoped>
.main-image {
  position: relative;
}
.main-image .hero-content {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.7);
  display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  font-size :32px;
  font-weight: bold;
}
.join {
  padding: 20px;
}
.join .help-text{
  text-align: center;
  color: #aaa;
  font-size: 12px;
}
.join .button {
  padding: 10px 0;
}
.rules {
  background: #eee;
  padding: 20px;
}
.rules ul li {
  margin-bottom: 10px;
}
.rules ul li:last-child {
  margin-bottom: 0;
}
.download {
  padding: 20px;
  text-align: center;
}
.download h3 {
  margin-bottom: 10px;
  font-weight: bold;
}

.download-android {
  padding: 20px;
  text-align: center;
}
.download-android h3 {
  margin-bottom: 10px;
  font-weight: bold;
}

.a {
  font-weight: bold;
}

.b {
  font-weight: bold;
}

.c {
  font-weight: bold;
}
.d {
  font-weight: bold;
}

</style>
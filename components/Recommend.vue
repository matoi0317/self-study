<template>
  <div class="square">
    <div class="rules">
      <ul>
        <div class="a"><li><font color="red">・自習室のURLは09:50に配布します</font></li></div>
        <div class="b"><li><font color="red">・自習室は火・木・金に開放しています</font></li></div>
        <div class="c"><li><font color="red">・解放時間は10:00 ~ 17:00です</font></li></div>
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
  </div>
</template>
<script>
export default {
  name: "Recommend"
}
</script>
<style scoped>
.square {
    width: 500px;
    height: 340px;
    border:solid #00d1b2;
    position: fixed;
    right: 2%;
    top: 40%;
    border-radius: 5px;
}

.rules {
  position: absolute;
  left: 10px;
  top: 10px;
  font-weight: bold;
}

</style>
<template>
  <div>
    <div class="head">
      <div class="name">ガリ勉自習室</div>
      <div class="twitter">
        <span class="icon is-large">
          <span class="icon has-text-info">
            <span class="fas fa-3x">
              <span class="icon">
                <i class="fab fa-twitter"></i>
              </span>
            </span>
          </span>
        </span>
      </div>
    </div> 
    <div class="download">
      <h3>ZOOMのダウンロードはこちら</h3>
      <a href="https://apps.apple.com/jp/app/zoom-cloud-meetings/id546505307" class="button is-primary is-fullwifth">
        ZOOMをダウンロード
      </a>
    </div>
  </div>
</template>
<script>
export default {
  name: "Head"
}
</script>

<style scoped>
.head {
  position: fixed;
  width:100%;
  height: 15%;
  border: 0.5px solid #DBDBDB;
  background-color:white;
}

.name {
  color: black;
  font-weight: bold;
  font-size: 80px;
  position: absolute;
  top: 0%;
  left:30%;
}

.download {
  position: absolute;
  right: 3%;
  padding: 20px;
  text-align: center;
}
.download h3 {
  margin-bottom: 10px;
  font-weight: bold;
}

.twitter {
  position: absolute;
  top: 30%;
  left: 10%;
}

</style>
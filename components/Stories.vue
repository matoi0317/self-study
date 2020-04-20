<template>
    <div class="join">
        <a href="" class="button is-primary is-fullwidth">
            ガリ勉自習室に参加する
        </a>
        <div class="help-text">ZOOMが自動的に開きます</div>
    </div>
</template>

<script>
export default {
  name: "Stories"
}
</script>

<style scoped>

.join {
  padding: 30px;
}
.join .help-text{
  text-align: center;
  color: #aaa;
  font-size: 20px;
    position: absolute;
    right: 150px;
    top: 230px;
    font-weight: bold;
}
.join .button {
    font-size: 30px;
    font-weight: bold;
    position: absolute;
    right: 30px;
    top: 130px;
  padding: 10px 0;
  height: 100px;
  width: 500px;
}




</style>
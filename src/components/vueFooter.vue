<template>
  <body>
  <footer id="page-footer">
    <div class="addr">
      <p style="text-align: center;">©2023 逢甲大學Feng Chia University<br>
        Copyright2014(c)逢甲大學Feng Chia University Powered by Moodle.<br>
        台中市西屯區文華路100號+886-4-24517250轉2129 隱私權聲明<br>
        本站最佳瀏覽解析度為 1024a*768以上
      </p>
    </div>
  </footer>
  </body>
</template>

<script>
export default {
  name: "vueFooter"
}
</script>

<style scoped>
body {
  line-height: 20px;
  text-shadow: none;
  font-size: 14px;
  background-color: rgba(255, 255, 255, .6);
  background-size: cover;
  margin: 0;
  padding: 0;
}

*, p {
  font-family: "Verdana";
}

img {
  vertical-align: bottom;
  max-width: 100%;
  height: auto;
}

.nav-links a {
  text-decoration: none;
  display: flex;
  padding: 10px 7px;
  color: #FFF;
}

.nav-links a:hover {
  background-color: #FFF;
  color: #99000F;
}

#page-footer {
  background-color: #99000F;
  color: #DDD;
  border-top: 2px solid #99000F;
  border-bottom: 3px solid #99000F;
  position: absolute;
  bottom: 0;
  height: 150px;
  width: 100%;
}

.addr {
  display: flex;
  align-items: end;
  justify-content: center;
  height: 150px;
}
</style>
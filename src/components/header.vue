<template>
  <body>
  <div id="page-header">
    <div class="flex-container">
      <div>
        <img src="//ilearn2.fcu.edu.tw/pluginfile.php/1/theme_essential/logo/1682046989/banner6_%E4%BF%AE2.jpg"
             class="img-responsive" alt="首頁">
      </div>
    </div>
    <nav class="row">
      <div class="navbar">
        <a class="logo" href="#">首頁</a>
        <ul class="nav-links">
          <li><a href="#">教育訓練</a></li>
          <li><a href="#">交流園地</a></li>
          <li><a href="#">線上學習支援</a></li>
          <li><a href="#">language</a></li>
        </ul>
      </div>
    </nav>
  </div>
  </body>
</template>

<script>
export default {
  name: "header"
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

.navbar {
  display: flex;
  min-width: 1200px;
  background-color: #99000F;
  color: #FFF;
}

.flex-container {
  display: flex;
  align-items: center;
  justify-content: center;
}

img {
  vertical-align: bottom;
  max-width: 100%;
  height: auto;
}

.row {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 40px;
  padding-right: 20px;
  padding-left: 20px;
  background-color: #99000F;
}

.logo {
  display: flex;
  align-items: center;
  text-decoration: none;
  font-size: 14px;
  padding-right: 20px;
  color: #FFF;
}

.nav-links {
  list-style: none;
  display: flex;
  margin: 0;
  padding: 0;
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

</style>
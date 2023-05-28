<template>
  <div id="page-content">
    <div class="table-row">
      <div class="table-cell left">
        <h2>登入</h2>

        <div id="login">
          <div class="subcontent loginsub">
            <div class="loginform">

              <div class="form-label">
                <label for="username">帳號</label>
                <input type="text" name="username" id="username" size="10">
              </div>

              <div class="form-label">
                <label for="password">密碼</label>
                <input type="password" name="password" id="password" size="10">
              </div>

            </div>

            <div class="rememberpass">
              <input type="checkbox" name="rememberusername" id="rememberusername">
              <label for="rememberusername">記住帳號</label>
            </div>

            <div class="submit">
              <input type="submit" id="submit" value="登入">
            </div>

            <div class="nidforgetpass">
              <a href="#" target="_blank" style="text-decoration: none;color: #99000F;">NID Forget Password</a>
            </div>

            <div class="forgetpass">
              <a href="#" style="text-decoration: none;color: #99000F;">忘記帳號或密碼嗎？</a>
            </div>
          </div>
        </div>

        <div class="desc">您的瀏覽器必須啟動 Cookies 功能</div>
      </div>
      <div class="table-cell right">
        <br><br><br>
        <div class="f-col">
          <strong style="font-size:large;text-align:left;">請使用NID帳號/密碼登入平台。</strong>
        </div>
        <div class="s-col">
          <strong style="font-size:large;text-align:left;">欲變更NID密碼，請連結至&nbsp;
            <a href="#" target="_blank" rel="noreferrer noopener">&nbsp;
              <img src="https://netid.fcu.edu.tw/image/nidlogo.png" alt="NID">
            </a>
          </strong>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "vueBody"
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

#page-content {
  min-width: 1200px;
  margin: 20px auto;
  display: table;
}

.table-row {
  display: table-row;
}

.table-cell {
  display: table-cell;
  padding: 10px 0px;
  min-width: 600px;
  border: 1px solid #ccc;
}

.left {
  border-top-left-radius: 5px;
  border-bottom-left-radius: 5px;
  border-right: none;
}

.right {
  border-top-right-radius: 5px;
  border-bottom-right-radius: 5px;
  border-left: none;
}

#username, #password {
  border: 2px solid #ccc;
  border-radius: 5px;
}

#login, h2, .desc, .rememberpass, .submit, .forgetpass, .nidforgetpass {
  display: flex;
  justify-content: center;
}

#submit {
  background-color: #30add1;
  color: #FFFFFF;
  border: 1px solid #ccc;
  padding: 5px 10px;
}

#submit:hover {
  cursor: pointer;
  background-color: aqua;
}

.form-label {
  height: 40px;
}

.desc, .submit, .forgetpass, .nidforgetpass {
  height: 30px;
  padding: 5px;
}

.f-col, .s-col {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
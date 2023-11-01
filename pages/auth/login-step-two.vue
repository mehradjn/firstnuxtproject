<script setup >
</script>

<template>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">


  <div class="login-step">
    <div class="div">
      <div class="overlap">
        <div class="ellipse-1" />
        <div class="group">
          <div class="overlap-group">
            <div class="ellipse-2" />
          </div>
        </div>
        <div class="active-line" />
        <div class="ellipse-3" />
        <p class="display">
          Compelete Backup <br />
          Soloution For All Devices
        </p>
        <p class="text-wrapper">Create your own website with the Fastest Page Building Platform.</p>
        <img class="img" alt="Group" src="/desktop-cam.svg" />
        <div class="ellipse-4" />
        <img class="restorage-logo" alt="Restorage logo" src="/Restorage-sec-log.svg" />
        <img class="mobile" alt="Mobile" src="/Mobile.svg" />
      </div>
      <div class="ellipse-5" />
      <div class="ellipse-6" />
      <header class="header">
        <div class="sign-up">
          <div class="text-wrapper-2">Not a member?</div>
          <button class="button">
            <div class="div-wrapper">
              <div class="text-wrapper-3">Sign up now</div>
            </div>
          </button>
        </div>
      </header>
      <div class="frame">
        <div class="group-2">
          <p class="p">
            <span class="span">Sign in to Restorage</span>
            <span class="text-wrapper-4">.</span>
          </p>
          <div class="display-2">Enter your detail below</div>
        </div>
        <div class="form">
          <div class="group-3">
            <div class="display-3">Username or Email</div>
            <div class="overlap-group-2">
              <div class="group-4">
                <div class="email-wrapper">
                  <div class="email">
                    <label class="text-wrapper" for="input-2">
                    </label>
                    <div class="overlap-group-4">
                      <div class="email-2">
                        <input class="email-address" id="input-2" placeholder="Email address" type="email" />
                        <img class="subtract" alt="Subtract" src="/Frame (1).svg" />
                      </div>
                    </div>
                  </div>
                </div>
             </div>
          </div>
          <div class="group-5">
            <div class="overlap-2">
              <div class="display-4">Password</div>
              <div class="display-5">Forget password?</div>
            </div>
              <div class="group-6">
                <div class="password-wrapper">
                  <div class="password">
                    <label class="text-wrapper" for="input-2">
                    </label>
                    <div class="overlap-group-5">
                      <div class="password-2">
                        <input class="password" id="input-2" value="Password" type="password" />
                        <img class="lock" alt="Lock" src="/Lock.svg" />
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          <button class="button-2">
            <div class="text-wrapper-7">Sign in</div>
          </button>
        </div>
      </div>
      <div class="ellipse-7" />
      <img class="cube" alt="Cube" src="cube.png" />
    </div>
  </div>
  </div>















</template>



<style scoped>
*,
*::before,
*::after{
  box-sizing: border-box;
}

*{
  margin: 0;
  padding: 0;
}


.login-step {
  background-color: #ffffff;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
}

.login-step .div {
  height: 1024px;
  overflow: hidden;
  position: relative;
  width: 1440px;
}

.login-step .overlap {
  height: 1265px;
  left: -400px;
  position: absolute;
  top: -283px;
  width: 1181px;
}

.login-step .ellipse-1 {
  background-color: #5956E9;
  border-radius: 50%;
  height: 1100px;
  left: 79px;
  position: absolute;
  top: -60px;
  width: 1100px;
}

.login-step .group {
  border-radius: 550px;
  height: 1100px;
  left: 0;
  position: absolute;
  top: 0;
  width: 1100px;
}

.login-step .overlap-group {
  background-size: 100% 100%;
  height: 817px;
  left: 400px;
  position: relative;
  top: 283px;
  width: 700px;
}

.login-step .ellipse-2 {
  background-color: #ffffff;
  border: 1px solid;
  border-radius: 318px;
  height: 636px;
  opacity: 0.1;
  position: relative;
  top: 104px;
  width: 636px;
}

.login-step .active-line {
  border-radius: 4px;
  height: 2px;
  left: 705px;
  position: absolute;
  top: 385px;
  width: 69px;
}

.login-step .ellipse-3 {
  background-color: #FAB8C4;
  border-radius: 64px;
  height: 128px;
  left: 950px;
  position: absolute;
  top: 527px;
  width: 128px;
}

.login-step .display {
  left: 500px;
  position: absolute;
  top: 454px;
  width: 443px;
}

.login-step .text-wrapper {
  left: 501px;
  opacity: 0.7;
  position: absolute;
  top: 622px;
  width: 279px;
}

.login-step .img {
  height: 515px;
  left: 434px;
  position: absolute;
  top: 696px;
  width: 747px;
}

.login-step .ellipse-4 {
  border-radius: 12px;
  height: 24px;
  left: 873px;
  position: absolute;
  top: 371px;
  width: 24px;
}

.login-step .restorage-logo {
  height: 39px;
  left: 498px;
  position: absolute;
  top: 351px;
  width: 173px;
}

.login-step .mobile {
  height: 298px;
  left: 400px;
  position: absolute;
  top: 967px;
  width: 629px;
}

.login-step .ellipse-5 {
  background-color: #FAB8C4;
  border-radius: 33.5px;
  height: 67px;
  left: 1273px;
  position: absolute;
  top: 761px;
  width: 67px;
}

.login-step .ellipse-6 {
  background-color: #FFDC60;
  border-radius: 16px;
  height: 32px;
  left: 848px;
  position: absolute;
  top: 68px;
  width: 32px;
}

.login-step .header {
  background-color: transparent;
  height: 72px;
  left: 1009px;
  position: absolute;
  top: 48px;
  width: 331px;
}

.login-step .sign-up {
  height: 72px;
  position: relative;
  width: 333px;
}

.login-step .text-wrapper-2 {
  font-family: "Poppins-Medium", Helvetica;
  font-size: 16px;
  font-weight: 500;
  left: 0;
  letter-spacing: 0;
  line-height: normal;
  position: absolute;
  top: 24px;
}

.login-step .button {
  all: unset;
  box-sizing: border-box;
  height: 72px;
  left: 158px;
  position: absolute;
  top: 0;
  width: 175px;
}

.login-step .div-wrapper {
  border-radius: 20px;
  height: 72px;
  position: relative;
  width: 173px;
}

.login-step .text-wrapper-3 {
  left: 40px;
  position: absolute;
  text-align: center;
  top: 24px;
  width: 173px;
}

.login-step .frame {
  height: 488px;
  left: 847px;
  position: absolute;
  top: 268px;
  width: 443px;
}

.login-step .group-2 {
  height: 88px;
  left: 0;
  position: absolute;
  top: 0;
  width: 447px;
}

.login-step .p {
  color: transparent;
  font-family: "DM Sans-Medium", Helvetica;
  font-size: 48px;
  font-weight: 500;
  left: 0;
  letter-spacing: -2.16px;
  line-height: 48px;
  top: 0;
  width: 443px;
}

.login-step .span {
  color: #28282f;
}

.login-step .text-wrapper-4 {
  color: #5956e8;
}

.login-step .display-2 {
  color: #999fae;
  font-family: "Poppins-Regular", Helvetica;
  font-size: 16px;
  font-weight: 400;
  left: 0;
  letter-spacing: -0.4px;
  line-height: 24px;
  top: 64px;
  width: 443px;
  position: absolute;
}

.login-step .form {
  height: 362px;
  left: 0;
  position: absolute;
  top: 136px;
  width: 387px;
}

.login-step .group-3 {
  height: 110px;
  left: 0;
  position: absolute;
  top: 6px;
  width: 389px;
}

.login-step .display-3 {
  color: #28282f;
  font-family: "DM Sans-Medium", Helvetica;
  font-size: 14px;
  font-weight: 500;
  left: 0;
  letter-spacing: -0.35px;
  line-height: 13.9px;
  position: absolute;
  top: 0;
  width: 353px;
}

.login-step .overlap-group-2 {
  height: 80px;
  left: 0;
  position: absolute;
  top: 30px;
  width: 387px;
}

.login-step .group-4 {
  height: 24px;
  left: -2px;
  position: absolute;
  top: -152px;
  width: 210px;
}

.login-step  .email-wrapper {
  height: 108px;
  left: 0;
  position: absolute;
  top: 124px;
  width: 387px;
}

.login-step .email {
  height: 108px;
  position: relative;
  width: 389px;
}

.login-step  .overlap-group-4 {
  border: 1px solid #e3e6e9;
  border-radius: 16px;
  height: 72px;
  left: 1px;
  position: absolute;
  top: 36px;
  width: 386px;
}

.login-step  .email-2 {
  height: 25px;
  left: 31px;
  position: relative;
  top: 23px;
  width: 150px;
}

.login-step  .email-address {
  background: transparent;
  border: none;
  left: 40px;
  padding: 0;
  position: absolute;
  top: 0;
  white-space: nowrap;
}

.login-step .group-5 {
  height: 108px;
  left: 0;
  position: absolute;
  top: 140px;
  width: 391px;
}

.login-step .overlap-2 {
  height: 24px;
  left: 0;
  position: absolute;
  top: 0;
  width: 386px;
}

.login-step .display-4 {
  color: #28282f;
  left: 0;
  position: absolute;
  top: 6px;
  width: 353px;
}

.login-step .display-5 {
  font-family: "Poppins-Regular", Helvetica;
  font-size: 14px;
  font-weight: 400;
  left: 267px;
  letter-spacing: -0.35px;
  line-height: 24px;
  position: absolute;
  text-align: right;
  top: 0;
  white-space: nowrap;
}


.login-step .group-6 {
  height: 24px;
  left: 31px;
  position: relative;
  top: 23px;
  width: 117px;
}

.login-step .password-wrapper {
  height: 108px;
  left: 0;
  position: absolute;
  top: 124px;
  width: 387px;
}

.login-step .password-wrapper {
  height: 108px;
  left: -38px;
  position: absolute;
  top: 256px;
  width: 389px;
}

.login-step .overlap-group-5 {
  border: 1px solid #e3e6e9;
  border-radius: 16px;
  height: 72px;
  left: -32px;
  position: absolute;
  top: -232px;
  width: 386px;
}

.login-step .password-2 {
  height: 25px;
  left: 31px;
  position: relative;
  top: 23px;
  width: 150px;
}

.login-step .password {
  background: transparent;
  border: none;
  left: 40px;
  padding: 0;
  position: absolute;
  top: 0;
  white-space: nowrap;
}

.login-step .button-2 {
  border-radius: 20px;
  box-sizing: border-box;
  height: 72px;
  left: 0;
  position: absolute;
  top: 280px;
  width: 213px;
}

.login-step .text-wrapper-7 {
  left: 81px;
  position: absolute;
  text-align: center;
  top: 24px;
  width: 51px;
}

.login-step .ellipse-7 {
  background-color: #FFDC60;
  border-radius: 106.5px;
  height: 213px;
  left: 955px;
  position: absolute;
  top: 918px;
  width: 213px;
}

.login-step .cube {
  height: 129px;
  left: 1355px;
  position: absolute;
  top: 473px;
  width: 85px;
}




@media (max-width: 460px){
  .login-step .frame{
    height: 488px;
    left: 3px;
    position: absolute;
    top: 62px;
    width: 275px;
  }

  .login-step .img {
    height: 515px;
    left: 427px;
    position: absolute;
    top: 717px;
    width: 500px;
  }
  .login-step .p {
    color: transparent;
    font-family: "DM Sans-Medium", Helvetica;
    font-size: 40px;
    font-weight: 500;
    left: 0;
    letter-spacing: -2.16px;
    line-height: 155px;
    top: 0;
    width: 443px;
  }
  .login-step .display-2 {
    color: #999fae;
    font-family: "Poppins-Regular", Helvetica;
    font-size: 20px;
    font-weight: 400;
    left: 0;
    letter-spacing: -0.4px;
    line-height: 24px;
    top: 102px;
    width: 443px;
    position: absolute;
  }
  .login-step .overlap-group-4 {
    border: 1px solid #e3e6e9;
    border-radius: 16px;
    height: 72px;
    left: 1px;
    position: absolute;
    top: 36px;
    width: 275px;
  }
  .login-step .overlap-group-5 {
    border: 1px solid #e3e6e9;
    border-radius: 16px;
    height: 72px;
    left: -32px;
    position: absolute;
    top: -232px;
    width: 275px;
  }
  .login-step .display-5 {
    font-family: "Poppins-Regular", Helvetica;
    font-size: 14px;
    font-weight: 400;
    left: 158px;
    letter-spacing: -0.35px;
    line-height: 52px;
    position: absolute;
    text-align: right;
    top: 0;
    white-space: nowrap;
  }
  .login-step .display-3 {
    color: #28282f;
    font-family: "DM Sans-Medium", Helvetica;
    font-size: 14px;
    font-weight: 500;
    left: 0;
    letter-spacing: -0.35px;
    line-height: 35.9px;
    position: absolute;
    top: 0;
    width: 353px;
  }
  .login-step .display-4 {
    color: #28282f;
    left: 0;
    position: absolute;
    top: 18px;
    width: 353px;
  }
  .login-step .button-2 {
    border-radius: 20px;
    box-sizing: border-box;
    height: 50px;
    left: 0;
    position: absolute;
    top: 280px;
    width: 113px;
  }
  .login-step .text-wrapper-7 {
    text-align: center;
  }
  .login-step .text-wrapper-7 {
    left: 29px;
    position: absolute;
    top: 16px;
    width: 51px;
  }
  .login-step .display {
    all: unset;
  }
  .login-step .text-wrapper {
    all: unset;
  }
}
</style>
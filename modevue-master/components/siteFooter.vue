<template>
  <v-container fluid pa-0>
    <v-row no-gutters class="rocketSection">
      <img class="" src="~assets/imgs/rocket.png" />
    </v-row>
    <v-row no-gutters class="bottomFooter">
      <div class="leftFooter">
        <div class="logo"><FooterLogo /></div>
        <div class="menuFooter">
          <span>Home</span>
          <span>Our Solutions</span>
          <span>Login/Sign-up</span>
          <span>FAQs</span>
        </div>
        <div class="textFooter">© 2020 Infinity Guild. All rights reserved</div>
      </div>
      <div class="rightFooter">
        <div class="joinUs">Join Us</div>
        <div class="btnFooter">
          <button class="menuBtn">
            <twitterIcon />
            <span>Twitter</span>
          </button>

          <button class="menuBtn">
            <discordIcon />
            <span>Discord</span>
          </button>
        </div>
      </div>
    </v-row>
  </v-container>
</template>

<style scoped>
@media all and (max-width: 960px) {
  .menuFooter {
    flex-direction: column;
  }
}
.rocketSection {
  background: #ff8b00;
}
.rocketSection img {
  width: 100%;
}
.bottomFooter {
  background: #231f20;
  padding: 100px 150px;

  display: flex;
  justify-content: space-between;
}
.leftFooter {
  display: flex;
  flex-direction: column;
}
.menuFooter {
  display: flex;
  margin: 30px 0;
}
.menuFooter span {
  font-family: Neue;
  font-size: 27px;
  font-style: normal;
  font-weight: 700;
  line-height: 44px;
  letter-spacing: 0em;
  text-align: left;
  margin-right: 40px;
  color: #83b5d1;
}
.textFooter {
  font-family: Neue;
  font-size: 14px;
  font-style: normal;
  font-weight: 400;
  line-height: 24px;
  letter-spacing: 0em;
  text-align: left;
  color: #d9dbe1;
}
.joinUs {
  font-family: Neue;
  font-size: 18px;
  font-style: normal;
  font-weight: 500;
  line-height: 28px;
  letter-spacing: 0em;
  text-align: left;
  color: #d9dbe1;
}
.rightFooter {
  margin-top: 55px;
}
.btnFooter {
  display: flex;
}

.menuBtn {
  height: 39px;
  width: 99px;
  border-radius: 8px;
  background: #ff8b00;
  border: solid 3px #fff;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-right: 10px;
}

.menuBtn span {
  font-family: Neue;
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
  line-height: 20px;
  letter-spacing: 0px;
  text-align: center;
  color: #ffffff;
  margin-left: 4px;
}

@media only screen and (max-width: 600px) {
  .bottomFooter {
    padding: 100px 30px;
    flex-direction: column;
  }
}
</style>

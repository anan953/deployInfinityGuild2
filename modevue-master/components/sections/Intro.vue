<template>
  <v-container fluid pa-0>
    <!-- Infinity Force section -->
    <v-row class="infinityForce">
      <v-col md="6" sm="12" class="leftinfinityForce">
        <div class="infinityForceTitle leftBanner">
          Play-to-Earn<br />
          Guild <br />Management <br />for the <br />Metaverse.
        </div>
        <div class="infinityForceSubtext">
          Infinity Force provides P2E managers and players the world’s first
          cross-chain software to build and grow guilds, issue automated
          payments and manage the team online with ease.
        </div>
        <button class="bigButton">
          <span>CONTACT US</span>
        </button>
      </v-col>
    </v-row>

    <!-- Banner section -->
    <v-row class="banner">
      <v-col md="6" cols="12" class="leftBanner">
        Build your Play-to-Earn Gaming Guild</v-col
      >
      <v-col md="6" cols="12" class="rightBanner">
        Access a unified view of players' performance and revenue data with
        advanced analytics, reporting tools and frictionless online transactions
        — in one single platform.</v-col
      ><v-col md="12" cols="12" class="bannerImg">
        <div class="highlightImage"></div
      ></v-col>
    </v-row>

    <v-row no-gutters class="IntroSection" justify="space-between">
      <v-col cols="12" class="IntroSectionTitle">
        WE MAKE THE DIGITAL REVOLUTION WORK FOR EVERYONE.
      </v-col>

      <v-col md="12" cols="12" class="IntroSectionText">
        <div class="IntroSectionText IntroSectionLeft">
          We provide the infrastructure to help communities reach their full
          potential by connecting players and guild managers in the Metaverse.
          From competitive gamers to content creators, artists and musicians,
          Infinity Force is the world’s first cross-chain software that unifies
          game enthusiasts worldwide. Income for your players. Return on
          investment for you.
        </div>
      </v-col>
    </v-row>

    <!-- How it works section -->
    <v-row no-gutters class="HowItWorks">
      <div class="HowItWorksWrap">
        <v-row no-gutters class="HowItWorksTitle">
          <span> >>>>> </span>
          <span> HOW IT WORKS </span>
          <span> &lt;&lt;&lt;&lt;&lt; </span>
        </v-row>

        <v-row no-gutters>
          <v-col cols="12" md="4" class="ImgSection">
            <img class="HowImg" src="~assets/imgs/icon-01.png" />
            <p class="HowImgTitle">BUILD YOUR GUILD</p>
            <p class="HowImgText">
              A guild is your play to earn gaming team. Earn revenue by
              registering as a Manager and connect to a global pool of skilled
              players. Infinity Force allows you to create and manage your own
              guild, communicate with players, enhance gameplay and strategize
              better with real-time data and training tools.
            </p>
          </v-col>
          <v-col cols="12" md="4" class="ImgSection">
            <img class="HowImg" src="~assets/imgs/icon-02.png" />
            <p class="HowImgTitle">GUILD PERFORMANCE MANAGEMENT</p>
            <p class="HowImgText">
              Access real-time data, player performance monitoring and automated
              payments in just a few clicks. Infinity Force provides the most
              accurate game insights and strong understanding of your team's
              core metrics.
            </p>
          </v-col>

          <v-col cols="12" md="4" class="ImgSection ImgSectionLast">
            <img class="HowImg" src="~assets/imgs/icon-03.png" />
            <p class="HowImgTitle">DATA & ANALYTICS</p>
            <p class="HowImgText">
              Access enhanced reporting and analytics to optimise your guild and
              player performance. View leaderboards of internal players, global
              guilds to foster increased competition across players. Infinity
              Force has game analytics, triggered alerts, graphs, automated
              insights, and forecast earning data to allow you to understand
              your future earnings potential.
            </p>
          </v-col>
        </v-row>
      </div>
    </v-row>
    <!-- Community section -->
    <v-row no-gutters class="CommunitySection">
      <v-col cols="12" md="6" class="CommunityLeft">
        <p>JOIN A GLOBAL COMMUNITY</p>
      </v-col>

      <v-col cols="12" md="6" class="Community">
        <p class="CommunityText">
          What makes play-to-earn technology so revolutionary is its ability to
          activate guilds and empower local communities from anywhere in the
          world. We invest in NFT assets to provide powerful opportunities for
          communities in need. And we are proud to be in the business of helping
          improve lives. Player? Manager? Join us!
        </p>

        <button class="bigButton">
          <joinDiscordIcon />
          <span>JOIN OUR DISCORD</span>
        </button>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.infinityForce {
  height: 976px;
  width: 100%;
  background-image: url(~assets/imgs/InfinityForceHomepage.jpg);
  background-repeat: no-repeat;
  background-size: 100% 100%;
  padding: 137px 150px 0px 150px;
  margin: 0;
}
.infinityForceSubtext {
  font-family: Neue;
  font-size: 20px;
  font-style: normal;
  font-weight: 700;
  line-height: 30px;
  letter-spacing: 0px;
  text-align: left;
  color: #fff;
  margin: 80px 0;
}
.banner {
  height: 976px;
  width: 100%;
  background-image: url(~assets/imgs/bannerBG.png);
  background-repeat: no-repeat;
  background-size: 100% 100%;
  padding: 137px 150px 0px 150px;
  margin: 0;
}
.bannerImg {
  display: flex;
  align-items: center;
  justify-content: center;
}

.highlightImage {
  height: 706px;
  width: 742px;
  background-image: url(~assets/imgs/HighlightImage.png);
  background-repeat: no-repeat;
  background-size: 100% 100%;
}

.leftBanner {
  font-family: Eurostile;
  font-size: 5em;
  font-style: normal;
  font-weight: 900;
  line-height: 77px;
  letter-spacing: -1px;
  text-align: left;
  color: #231f20;
}
.rightBanner {
  font-family: Neue;
  font-size: 21px;
  font-style: normal;
  font-weight: 700;
  line-height: 30px;
  letter-spacing: 0px;
  text-align: left;
  color: #231f20;
}
.IntroSection {
  padding: 56px 140px 61px 174px;
  background: #ff8b00;
  margin-top: -1px;
}
.IntroSectionTitle {
  font-family: Eurostile;
  font-size: 3em;
  font-style: normal;
  font-weight: 900;
  line-height: 67px;
  letter-spacing: 0px;
  text-align: center;
  color: #231f20;
  margin-bottom: 49px;
}
.IntroSectionText {
  font-family: Neue;
  font-size: 19px;
  font-style: normal;
  font-weight: 700;
  line-height: 30px;
  letter-spacing: 0px;
  text-align: left;
  color: #ffffff;
  padding: 10px;
}
.HowItWorks {
  padding: 37px 50px 69px 50px;
  background: #ff8b00;
}
.HowItWorksWrap {
  min-height: 872px;
  width: 100%;
  background-image: url(~assets/imgs/HowItWorkBG.png);
  background-repeat: no-repeat;
  background-size: 100% 100%;
  padding: 81px 100px;
  margin-left: 25px;
}
.HowItWorksTitle {
  font-family: Eurostile;
  font-size: 75px;
  font-style: normal;
  font-weight: 900;
  line-height: 99px;
  letter-spacing: 1px;
  text-align: center;
  color: #ff8b00;
  display: flex;
  justify-content: center;
}
.HowImg {
  height: 280px;
  width: 280px;
}
.ImgSection {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
  padding: 30px !important;
}
.HowImgTitle {
  font-family: Eurostile;
  font-size: 30px;
  font-style: normal;
  font-weight: 900;
  line-height: 42px;
  letter-spacing: 0.02em;
  text-align: center;
  color: #ff8b00;
  margin: 15px 0 5px 0;
}
.HowImgText {
  font-family: Neue;
  font-size: 17px;
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
  letter-spacing: 0em;
  text-align: center;
  color: #ffffff;
  padding: 0 20px;
}

.CommunitySection {
  background: #ff8b00;
  padding: 10px 80px 80px 80px;
  min-height: 478px;
}
.CommunityLeft p {
  font-family: Eurostile;
  font-size: 82px;
  font-style: normal;
  font-weight: 900;
  line-height: 77px;
  letter-spacing: 0px;
  text-align: left;
  color: #231f20;
}
.CommunityLeft {
  background-image: url(~assets/imgs/communityLeftBG.png);
  background-repeat: no-repeat;
  background-size: 100% 100%;
  padding: 100px 100px 100px 150px !important;
}

.Community {
  display: flex;
  flex-direction: column;
  padding: 20px 50px !important;
}

.bigButton {
  height: 80px;
  width: 338px;
  border-radius: 21px;
  padding: 8px;
  background: #83b5d1;
  border: 8px solid #ffffff;
  display: flex;
  flex-direction: center;
  align-items: center;
  justify-content: center;
}
.bigButton span {
  font-family: Neue;
  font-size: 24px;
  font-style: normal;
  font-weight: 700;
  line-height: 37px;
  letter-spacing: 0px;
  text-align: center;
  color: #fff;
  margin-left: 10px;
}
.Community {
  display: flex;
  flex-direction: column;
  padding: 20px !important;
}
.CommunityTitle {
  font-family: Eurostile;
  font-size: 82px;
  font-style: normal;
  font-weight: 900;
  line-height: 77px;
  letter-spacing: 0px;
  text-align: left;
  color: #231f20;
}
.CommunityText {
  font-family: Neue;
  font-size: 21px;
  font-style: normal;
  font-weight: 700;
  line-height: 30px;
  letter-spacing: 0px;
  text-align: left;
  color: #fff;
  margin: 80px 0;
}
.CommunityImg {
  width: 100%;
}

@media only screen and (max-width: 600px) {
  .banner {
    padding: 80px 10px 0px 10px;
  }

  .IntroSection {
    padding: 30px 10px 0px 10px;
  }

  .IntroSectionText {
    margin-bottom: 30px;
    font-size: 19px !important;
  }

  .HowItWorksWrap {
    padding: 130px 100px;
  }

  .ImgSection {
    padding: 0 !important;
    margin-bottom: 60px !important;
  }

  .HowItWorks {
    padding: 37px 20px 69px 20px;
  }

  .CommunityLeft {
    padding: 10px 50px 10px 0px !important;
  }

  .Community {
    padding: 0px !important;
  }

  .CommunitySection {
    padding: 10px 20px 80px 20px;
  }
}
@media all and (min-width: 960px) {
  .IntroSectionLeft {
    padding-right: 17px;
  }
  .IntroSectionRight {
    padding-left: 17px;
  }
}
@media all and (max-width: 600px) {
  .HowItWorksTitle {
    font-size: 38px !important;
    letter-spacing: 0px !important;
    line-height: 57px !important;
  }
  .leftBanner {
    font-size: 3.5em !important;
    line-height: 55px !important;
  }
  .infinityForce {
    padding: 20px 0 !important;
    background-color: #ff8b00 !important;
    background-image: none !important;
    height: auto !important;
  }
  .IntroSectionTitle {
    font-size: 3em !important;
    line-height: 44px !important;
    margin-bottom: 50px !important;
  }
  .CommunityLeft p {
    font-size: 58px !important;
    line-height: 51px !important;
  }
  .HowItWorksWrap {
    background-image: url(~assets/imgs/HowIsWorkBGMobile.png) !important;
    padding: 20px !important;
    margin-left: 0 !important;
  }
  .highlightImage {
    height: 435px !important;
    background-image: url(~assets/imgs/HighlighImageMobile.png) !important;
  }
  .infinityForceSubtext {
    margin: 40px 0 !important;
  }
  .CommunityText {
    font-size: 18px;
    margin: 30px 0 50px 0;
  }
}
</style>

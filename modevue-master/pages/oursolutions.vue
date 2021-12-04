<template>
  <v-container fluid pa-0>
    <v-row no-gutters class="aboutSection">
      <v-row no-gutters class="">
        <p class="aboutUsTitle">Our Solutions</p>
      </v-row>
      <v-row no-gutters class="ourVision">
        <v-col cols="12" md="6" class="ourVisionLeft">
          <div class="ourVisionTitle">INFINITY FORCE.</div>
          <div class="ourVisionText">
            To inspire NFT gamers to thrive while advancing the world’s shift to
            the digital economy.
          </div>
        </v-col>

        <v-col cols="12" md="6" class="ourVisionRight">
          <div class="ourVisionRightText">
            Infinity Force is the key to introducing more immersion into the NFT
            gaming industry. Our management platform reduces friction in online
            transactions, bridges gaps by connecting game players, managers and
            investors to play to earn games.
          </div>
        </v-col>
      </v-row>
    </v-row>

    <v-row no-gutters class="aboutPhotoSection">
      <img src="~assets/imgs/aboutPhoto.png" />
    </v-row>
    <!-- Our mission section -->
    <v-row no-gutters class="ourMission">
      <div class="ourMissionWrap">
        <v-row no-gutters>
          <v-col cols="12" md="6" class="ourMissionTitle">
            <p>OUR SOLUTION.</p>
          </v-col>
          <v-col cols="12" md="6" class="ourMissionText">
            <p>
              We know the challenges of managing your guild so we created the
              solution. Infinity Force provides end-to-end automation
              capabilities allowing teams to be managed at maximum efficiency.
              Focused on new Player Onboarding, Dashboard Analytics, Player
              Performance Monitoring & Payments Automation. Infinity Force was
              developed to eliminate entry barriers to P2E games due to tedious
              manual operations, in-game challenges, and lack of fundamental
              knowledge and training resources to both players and managers. We
              want to drive change and innovation in the P2E ecosystem by
              providing a platform that connects all P2E game enthusiasts to one
              central management system. Infinity Force enables users to build
              their own guild, simplify operations, train and develop players
              through automated recruitment and onboarding, advanced performance
              management tools, payment automation and data analytics.
            </p>
          </v-col>
        </v-row>
      </div>
    </v-row>
    <!-- Community section -->
    <v-row no-gutters class="CommunitySection">
      <v-col cols="12" md="6" class="CommunityLeft">
        <p>GROW YOUR GUILD</p>
      </v-col>

      <v-col cols="12" md="6" class="Community">
        <p class="CommunityText">
          Infinity Force is your gateway to NFT gaming management with built-in
          automation. Finance players and receive a percentage of their earnings
          in a blockchain-based economy that lets you leverage De-Fi to scale at
          speed.
        </p>

        <button class="DiscordBtn">
          <joinDiscordIcon />
          <span>JOIN OUR DISCORD</span>
        </button>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
@media all and (max-width: 960px) {
  .ourMission {
    padding: 0 !important;
  }
  .ourMissionWrap {
    background-image: none !important;
    background-color: #fff;
    padding: 20px !important;
  }
}
.aboutSection {
  width: 100%;
  background-image: url(~assets/imgs/AboutUsTopBg.png);
  background-repeat: no-repeat;
  background-size: 100% 100%;
  padding: 59px 150px 120px 150px;
}
.aboutUsTitle {
  font-family: Neue;
  font-size: 24px;
  font-style: normal;
  font-weight: 700;
  line-height: 37px;
  letter-spacing: 0px;
  text-align: left;
  color: #ffffff;
  margin-bottom: 36px;
}
.ourVisionTitle {
  font-family: Eurostile;
  font-size: 68px;
  font-style: normal;
  font-weight: bolder;
  line-height: 77px;
  letter-spacing: 0px;
  text-align: left;
  color: #231f20;
  margin-bottom: 10px;
}
.ourVisionText {
  font-family: Eurostile;
  font-size: 33px;
  font-style: normal;
  font-weight: 700;
  line-height: 40px;
  letter-spacing: 0px;
  text-align: left;
  color: #231f20;
}
.ourVisionRightText {
  font-family: Neue;
  font-size: 21px;
  font-style: normal;
  font-weight: 700;
  line-height: 30px;
  letter-spacing: 1px;
  text-align: left;
  color: #ffffff;
}
.ourVisionLeft {
  padding-right: 18px !important;
}
.ourVisionRight {
  padding-left: 18px !important;
}
.aboutPhotoSection {
  background: #ff8b00;
  padding: 40px;
}

.aboutPhotoSection img {
  width: 100%;
  height: 100%;
}
.ourMission {
  padding: 37px 50px 69px 50px;
  background: #ff8b00;
}
.ourMissionWrap {
  min-height: 328px;
  width: 100%;
  background-image: url(~assets/imgs/ourMissionBG.png);
  background-repeat: no-repeat;
  background-size: 100% 100%;
  padding: 75px 100px;
}
.ourMissionTitle p {
  font-family: Eurostile;
  font-size: 70px;
  font-style: normal;
  font-weight: 900;
  line-height: 77px;
  letter-spacing: -1px;
  text-align: left;
  color: #231f20;
}
.ourMissionText p {
  font-family: Neue;
  font-size: 15px;
  font-style: normal;
  font-weight: 700;
  letter-spacing: 0px;
  text-align: left;
  color: #231f20;
}
.CommunitySection {
  background: #ff8b00;
  padding: 10px 80px 80px 80px;
  min-height: 478px;
}
.CommunityLeft p {
  font-family: Eurostile;
  font-size: 6em;
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

.DiscordBtn {
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
.DiscordBtn span {
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

@media only screen and (max-width: 600px) {
  .aboutSection {
    padding: 59px 40px 50px 40px;
  }

  .ourVisionTitle {
    margin-bottom: 40px;
  }

  .ourVisionText {
    margin-bottom: 40px;
  }

  .ourVisionRight {
    padding: 0px !important;
  }

  .ourMissionWrap {
    padding: 75px 30px;
  }

  .ourMissionTitle {
    margin-bottom: 30px;
  }

  .ourMissionText {
    margin-bottom: 50px;
  }

  .CommunityLeft {
    padding: 100px 50px 100px 0px !important;
  }

  .Community {
    padding: 0px !important;
  }

  .CommunitySection {
    padding: 10px 20px 80px 20px;
  }
}
</style>

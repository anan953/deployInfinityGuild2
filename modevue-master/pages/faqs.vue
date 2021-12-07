<template>
  <section>
    <v-row no-gutters>
      <v-col cols="12"
        ><div class="container-pr">
          <div class="content">
            <div class="faq-text">FAQs</div>

            <v-row no-gutters>
              <v-col cols="12" md="6">
                <div class="learn-more-text">LEARN MORE.</div>
              </v-col>

              <v-col cols="12" md="6">
                <div class="text-desc">
                  Here’s some common questions about Infinity Guild and how to
                  become part of the community.
                </div>
              </v-col>
            </v-row>

            <v-row no-gutters>
              <v-col cols="12">
                <div class="input-contanier">
                  <input placeholder="Search..." class="input-text" />

                  <v-img
                    class="icon-search"
                    height="25px"
                    width="25px"
                    contain
                    :src="`/brands/icon-search.svg`"
                  ></v-img>
                </div>
              </v-col>
            </v-row>

            <div class="center">
              <!-- question section 1 -->
              <div class="question-container">
                <div class="question1-wrap">
                  <v-row no-gutters>
                    <v-col cols="12" md="4" class="">
                      <span class="Started">GETTING STARTED</span>
                    </v-col>
                    <v-col cols="12" md="8" class="Started">
                      <div class="question">
                        <span class="question-content"
                          >This is a question that people ask?
                        </span>
                        <span class="plus-icon">+</span>
                      </div>
                      <div class="question">
                        <span class="question-content"
                          >This is a question that people ask?
                        </span>
                        <span class="plus-icon">+</span>
                      </div>
                      <div class="question">
                        <span class="question-content"
                          >This is a question that people ask?
                        </span>
                        <span class="plus-icon">+</span>
                      </div>
                      <div class="question">
                        <span class="question-content"
                          >This is a question that people ask?
                        </span>
                        <span class="plus-icon">+</span>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </div>

              <!-- Question section 2 -->
              <div class="question-container">
                <div class="question2-wrap">
                  <v-row no-gutters>
                    <v-col cols="12" md="4" class="">
                      <span class="Started">BECOMING A SCHOLAR</span>
                    </v-col>
                    <v-col cols="12" md="8" class="Started">
                      <div class="question">
                        <span class="question-content"
                          >This is a question that people ask?
                        </span>
                        <span class="plus-icon">+</span>
                      </div>
                      <div class="question">
                        <span class="question-content"
                          >This is a question that people ask?
                        </span>
                        <span class="plus-icon">+</span>
                      </div>
                      <div class="question">
                        <span class="question-content"
                          >This is a question that people ask?
                        </span>
                        <span class="plus-icon">+</span>
                      </div>
                      <div class="question">
                        <span class="question-content"
                          >This is a question that people ask?
                        </span>
                        <span class="plus-icon">+</span>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </div>

              <!-- Question section 3 -->
              <div class="question-container">
                <div class="question2-wrap">
                  <v-row no-gutters>
                    <v-col cols="12" md="4" class="">
                      <span class="Started">BECOMING A MANAGER</span>
                    </v-col>
                    <v-col cols="12" md="8" class="Started">
                      <div class="question">
                        <span class="question-content"
                          >This is a question that people ask?
                        </span>
                        <span class="plus-icon">+</span>
                      </div>
                      <div class="question">
                        <span class="question-content"
                          >This is a question that people ask?
                        </span>
                        <span class="plus-icon">+</span>
                      </div>
                      <div class="question">
                        <span class="question-content"
                          >This is a question that people ask?
                        </span>
                        <span class="plus-icon">+</span>
                      </div>
                      <div class="question">
                        <span class="question-content"
                          >This is a question that people ask?
                        </span>
                        <span class="plus-icon">+</span>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </div>
            </div>
          </div>
        </div>
      </v-col>
    </v-row>
    <!-- Community section -->
    <v-row no-gutters class="CommunitySection">
      <v-col cols="12" md="6" class="CommunityLeft">
        <p>JOIN OUR COMMUNITY</p>
      </v-col>

      <v-col cols="12" md="6" class="Community">
        <p class="CommunityText">
          What makes play-to-earn technology so revolutionary is its ability to
          activate guilds and empower local communities from anywhere in the
          world.
        </p>

        <button class="DiscordBtn">
          <joinDiscordIcon />
          <span>JOIN OUR DISCORD</span>
        </button>
      </v-col>
    </v-row>
  </section>
</template>

<style scoped>
.container-pr {
  min-height: 100vh;
  background-color: #83b5d1;
  width: 100%;
}

.content {
  padding: 57px 160px;
}

.faq-text {
  font-family: Neue;
  font-weight: bold;
  font-size: 24px;
  line-height: 36px;
  color: #ffffff;
  margin-bottom: 36px;
}

.learn-more-text {
  font-weight: 900;
  font-size: 76px;
  line-height: 76px;
  letter-spacing: -1px;
  color: #231f20;
  margin: 0;
  font-family: Eurostile;
  text-shadow: 3px 0 #231f20;
}

.text-desc {
  font-weight: 500;
  font-size: 21px;
  line-height: 30px;
  color: #000;
  margin: 0;
  font-family: Neue;
}

.input-contanier {
  position: relative;
  width: 100%;
}

.input-text {
  margin-top: 50px;
  width: 100%;
  height: 60px;
  background: #ffffff;
  border: 9px solid #231f20;
  border-radius: 22px;
  padding-left: 40px;
  padding-right: 40px;
}

.icon-search {
  position: absolute;
  right: 20px;
  z-index: 999;
  bottom: 15px;
}

.center {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 50px;
  flex-direction: column;
}

.question-container {
  margin-bottom: 50px;
  width: 100%;
  min-height: 402px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  background: #ffffff;
  box-shadow: 13px 14px 12px rgba(0, 0, 0, 0.25);
  border-radius: 21px;
  padding: 20px;
}
.question1-wrap {
  background-image: url(~assets/imgs/questionBG1.png);
  background-repeat: no-repeat;
  background-size: 100% 100%;
  padding: 65px 100px;
  height: 100%;
  width: 100%;
}

.question2-wrap {
  background-image: url(~assets/imgs/questionBG2.png);
  background-repeat: no-repeat;
  background-size: 100% 100%;
  padding: 65px 100px;
  height: 100%;
  width: 100%;
}
.Started {
  border-top: 1.73px solid #000000;
  width: 72%;
  display: inline-block;
  padding-top: 15px;

  font-weight: 850;
  font-size: 40px;
  line-height: 43px;
  color: #ff8b00;
  margin: 0;
  font-family: Eurostile;
}
.question-content {
  font-weight: 500;
  font-size: 21px;
  line-height: 32px;
  color: #000;
  cursor: pointer;
  font-family: Neue;
  text-align: left;
}
.plus-icon {
  font-weight: 500;
  font-size: 21px;
  line-height: 32px;
  color: #000;
  cursor: pointer;
  font-family: Neue;
}
.question {
  display: flex;
  justify-content: space-between;
  padding: 10px;
  border-bottom: 1.73px solid #000000;
}

.CommunitySection {
  background: #ff8b00;
  padding: 10px 80px 80px 80px;
  min-height: 478px;
}
.CommunityLeft p {
  font-family: Eurostile;
  font-weight: 900;
  font-size: 82px;
  line-height: 76px;
  color: #231f20;
  margin: 0;
  text-shadow: 4px 0 #231f20;
}
.CommunityLeft {
  background-image: url(~assets/imgs/leftcommunityBG.png);
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
  font-size: 20px;
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
  .content {
    padding: 57px 20px;
  }

  .question1-wrap {
    padding: 40px;
  }

  .question2-wrap {
    padding: 40px;
  }

  .question3-wrap {
    padding: 40px;
  }

  .Started {
    margin-bottom: 30px;
    font-size: 27px;
    line-height: 36px;
  }

  .CommunityLeft {
    padding: 10px 50px 10px 0px !important;
  }
  .CommunityText {
    font-size: 18px;
    margin: 20px 0 50px;
  }

  .Community {
    padding: 0px !important;
  }

  .CommunitySection {
    padding: 10px 20px 80px 20px;
  }
  .question1-wrap,
  .question2-wrap {
    background-image: url(~assets/imgs/questionMobileBG.png) !important;
  }
  .CommunityLeft p {
    font-size: 58px;
  }
  .learn-more-text {
    font-size: 60px;
    line-height: 60px;
  }
  .question-content {
    font-size: 17px;
    line-height: 23px;
  }
}
</style>

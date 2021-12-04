<template>
  <div>
    <v-navigation-drawer v-model="drawer" fixed app temporary>
      <v-list dense>
        <v-list-item-group v-for="(item, i) in items" :key="i" color="primary">
          <v-list-item v-if="!item.submenu" :to="item.to">
            <v-list-item-action>
              <v-icon>{{ item.icon }}</v-icon>
            </v-list-item-action>
            <v-list-item-content>
              <v-list-item-title v-text="item.title.toUpperCase()" />
            </v-list-item-content>
          </v-list-item>
          <v-list-group v-else :prepend-icon="item.icon" no-action>
            <template v-slot:activator>
              <v-list-item-content>
                <v-list-item-title
                  v-text="item.title.toUpperCase()"
                ></v-list-item-title>
              </v-list-item-content>
            </template>
            <v-list-item
              v-for="child in item.submenu"
              :key="child.title"
              :to="child.to"
            >
              <v-list-item-content>
                <v-list-item-title v-text="child.title"></v-list-item-title>
              </v-list-item-content>
            </v-list-item>
          </v-list-group>
        </v-list-item-group>
      </v-list>
    </v-navigation-drawer>

    <v-app-bar
      fixed
      app
      hide-on-scroll
      height="64"
      elevate-on-scroll
      class="wrapperMenu"
    >
      <div class="leftMenu">
        <v-app-bar-nav-icon class="hidden-md-and-up" @click="drawer = true" />
        <nuxt-link to="/" class="d-flex">
          <Logo />
        </nuxt-link>
        <v-spacer />

        <div class="menuItem">
          <template v-for="(name, menuitem) in items">
            <template v-if="name.submenu">
              <v-menu
                :key="menuitem"
                open-on-hover
                offset-y
                transition="slide-y-transition"
                bottom
              >
                <template v-slot:activator="{ on, attrs }">
                  <v-btn
                    plain
                    class="py-8 submenubtn hidden-sm-and-down menutext"
                    :ripple="false"
                    v-bind="attrs"
                    v-on="on"
                  >
                    {{ name.title }}
                    <v-icon right small class="mx-0"> mdi-chevron-down </v-icon>
                  </v-btn>
                </template>
                <v-list dense>
                  <v-list-item
                    v-for="(item, index) in name.submenu"
                    :key="index"
                    link
                    :to="item.to"
                    class="menutext"
                  >
                    <v-list-item-title>{{ item.title }}</v-list-item-title>
                  </v-list-item>
                </v-list>
              </v-menu>
            </template>
            <v-btn
              v-else
              :key="menuitem"
              depressed
              tile
              plain
              class="py-8 hidden-sm-and-down menutext"
              :to="name.to"
              >{{ name.title }}</v-btn
            > </template
          ><v-spacer />
        </div>
      </div>

      <div class="mobile-btn">
        <button class="menuBtn">
          <twitterIcon />
        </button>

        <button class="menuBtn">
          <discordIcon />
        </button>
      </div>

      <div class="rightMenu">
        <button class="menuBtn">
          <twitterIcon />
          <span>Twitter</span>
        </button>

        <button class="menuBtn">
          <discordIcon />
          <span>Discord</span>
        </button>
      </div>

      <!-- <v-btn icon @click="changeThemeColor">
        <v-icon>{{
          $vuetify.theme.dark ? 'mdi-white-balance-sunny' : 'mdi-weather-night'
        }}</v-icon>
      </v-btn> -->
    </v-app-bar>
  </div>
</template>

<script>
export default {
  data() {
    return {
      clipped: false,
      drawer: false,
      items: [
        {
          icon: 'mdi-folder-home-outline',
          title: 'Home',
          to: '/',
        },
        {
          icon: 'mdi-account',
          title: 'Our Solutions',
          to: '/oursolutions',
        },
        {
          icon: 'mdi-folder-image',
          title: 'Login/Sign-up',
          to: '/oursolutions',
        },
        {
          icon: 'mdi-cash-usd',
          title: 'FAQs',
          to: '/faqs',
        },
      ],
    }
  },
  methods: {
    // changeThemeColor() {
    //   if (this.$vuetify.theme.dark === true) {
    //     this.$vuetify.theme.dark = false
    //   } else {
    //     this.$vuetify.theme.dark = true
    //   }
    // },
  },
}
</script>

<style scoped>
.wrapperMenu {
  background-color: #231f20 !important;
  padding: 0 150px;
}

.v-btn > .v-btn__content .v-icon {
  color: #fff;
}

>>> .v-toolbar__content {
  justify-content: space-between;
}

.leftMenu {
  display: flex;
  align-items: center;
}

.rightMenu {
  display: flex;
  flex-direction: row;
  align-items: center;
}

.menuItem {
  margin-left: 32px;
}
.menutext {
  font-family: Neue;
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
  line-height: 20px;
  letter-spacing: 0px;
  text-align: left;
  color: #ffffff !important;
}
.submenubtn {
  cursor: default;
}
.menuBtn {
  height: 39px;
  width: 99px;
  border-radius: 8px;
  padding: 8px, 23px, 8px, 23px;
  background: #ff8b00;
  border: solid 3px #fff;
  display: flex;
  flex-direction: center;
  align-items: center;
  justify-content: center;
  margin-left: 18px;
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

.mobile-btn {
  display: none;
}

@media only screen and (max-width: 600px) {
  .wrapperMenu {
    padding: 0 !important;
  }

  .rightMenu {
    display: none;
  }

  .mobile-btn {
    display: flex;
  }

  .menuBtn {
    height: 40px;
    width: 40px;
  }
}
</style>

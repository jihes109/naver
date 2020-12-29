<template>
  <div id="app">
    <v-app id="inspire">
      <!-- Must have the app property -->
      <v-card class="mx-auto" width="256" tile>
        <v-navigation-drawer v-model="drawer" app>
          <v-system-bar></v-system-bar>
          <v-list>
            <v-list-item>
              <v-list-item-avatar>
                <v-img>
                  <img src="@/assets/img-me.jpg" alt="" />
                </v-img>
              </v-list-item-avatar>
            </v-list-item>

            <v-list-item link>
              <v-list-item-content>
                <v-list-item-title class="title">
                  퍼블리싱 연습장
                </v-list-item-title>
                <v-list-item-subtitle>jihes109@naver.com</v-list-item-subtitle>
              </v-list-item-content>

              <v-list-item-action>
                <v-icon>mdi-menu-down</v-icon>
              </v-list-item-action>
            </v-list-item>
          </v-list>
          <v-divider></v-divider>
          <v-list nav dense>
            <v-list-item-group v-model="selectedItem" color="primary">
              <v-list-item v-for="(item, i) in items" :key="i">
                <v-list-item-icon>
                  <v-icon v-text="item.icon"></v-icon>
                </v-list-item-icon>

                <v-list-item-content>
                  <v-list-item-title v-text="item.text"></v-list-item-title>
                </v-list-item-content>
              </v-list-item>
            </v-list-item-group>
          </v-list>
        </v-navigation-drawer>
      </v-card>

      <v-app-bar app>
        <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>

        <v-toolbar-title>Application</v-toolbar-title>
      </v-app-bar>

      <v-main>
        <div class="section-guide">
          <h1>NAVER</h1>
          <h2>그리드와 컴포넌트 요소</h2>
          <v-container class="top-search">
            <v-img class="">
              <img class="main-logo" src="@/assets/logo-naver.png" alt="" />
            </v-img>
            <v-text-field
              v-model="message2"
              solo
              label="Solo"
              clearable
            ></v-text-field>
            <v-btn tile color="success">
              <v-icon center>
                mdi-magnify
              </v-icon>
            </v-btn>
          </v-container>
          <v-container fluid>
            <v-row>
              <v-card>
                <v-tabs
                  success
                  background-color="white "
                  color="success"
                  show-arrows
                >
                  <v-tabs-slider color="teal lighten-3"></v-tabs-slider>

                  <v-tab v-for="(tablist, i) in tablist" :key="i">
                    <v-list-item-title
                      v-text="tablist.text"
                    ></v-list-item-title>
                  </v-tab>
                </v-tabs>
              </v-card>
            </v-row>
            <v-row>
              <v-col cols="12" sm="6">
                2
              </v-col>
              <v-col cols="12" sm="6">
                3
              </v-col>
            </v-row>
          </v-container>
        </div>
      </v-main>
    </v-app>
  </div>
</template>

<script>
// 좌측네비게이션 하단 리스트
export default {
  data: () => ({
    dialog: false,
    drawer: null,
    items: [
      { text: "네이버", icon: "mdi-account-outline" },
      { text: "토스", icon: "mdi-bike" },
      { text: "page", icon: "mdi-package-variant" },
      { text: "page", icon: "mdi-comment-processing-outline" },
      // { text: "Offline", icon: "mdi-check-circle" },
      // { text: "Uploads", icon: "mdi-upload" },
      // { text: "Backups", icon: "mdi-cloud-upload" },
    ],
    tablist: [
      { text: "메일" },
      { text: "카페" },
      { text: "블로그" },
      { text: "지식IN" },
      { text: "쇼핑" },
      { text: "PAY" },
      { text: "TV" },
      { text: "사전" },
      { text: "뉴스" },
      { text: "증권" },
      { text: "부동산" },
      { text: "지도" },
      { text: "영화" },
    ],
  }),
};
</script>

<style scoped>
@import "./assets/css/common.css";
.section-guide {
  padding: 20px;
}
.section-guide > h1,
.section-guide > h2 {
  padding-left: 10px;
  border-bottom: 1px solid #ddd;
}
</style>

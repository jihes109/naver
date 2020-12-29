<template>
  <body>
    <section class="form-center ">
      <div class="top-left ">
        <button class="button-s-grey "><h4>네이버를 시작페이지로</h4></button>
        <button class="button-s-grey"><h4>쥬니어네이버</h4></button>
        <button class="button-s-grey"><h4>해피빈</h4></button>
      </div>
      <div class="top-search">
        <img src="@/assets/logo-naver.png" class="logo-default" alt="" />
        <form class="search-input">
          <input type="text" class="inputbox" id="searchkey" name="searchkey" />
          <button class="btn-submit"><v-icon>mdi-magnify</v-icon></button>
        </form>
      </div>
    </section>
    <div class="nav-bg">
      <section class="group-nav ">
        <div class="group-nav-left">
          <ul class="list-nav">
            <li class="nav-item a-green">
              <a href=""><h3 class="primary">메일</h3></a>
            </li>
            <li class="nav-item a-green">
              <a href=""><h3 class="primary">카페</h3></a>
            </li>
            <li class="nav-item a-green">
              <a href=""><h3 class="primary">블로그</h3></a>
            </li>
            <li class="nav-item a-green">
              <a href=""><h3 class="primary">지식IN</h3></a>
            </li>
            <li class="nav-item a-green">
              <a href=""><h3 class="primary">쇼핑</h3></a>
            </li>
            <li class="nav-item a-green">
              <a href=""><h3 class="primary">PAY</h3></a>
            </li>
            <li class="nav-item a-green">
              <a href=""><h3 class="primary">TV</h3></a>
            </li>
            <li class="nav-item a-none">
              <a href=""><h3>사전</h3></a>
            </li>
            <li class="nav-item a-none">
              <a href=""><h3>뉴스</h3></a>
            </li>
            <li class="nav-item a-none">
              <a href=""><h3>부동산</h3></a>
            </li>
            <li class="nav-item a-none">
              <a href=""><h3>지도</h3></a>
            </li>
            <li class="nav-item a-none">
              <a href=""><h3>영화</h3></a>
            </li>
            <li class="nav-item a-none">
              <a href=""><h3>VIBE</h3></a>
            </li>
            <li class="nav-item a-none">
              <a href=""><h3>책</h3></a>
            </li>
            <li class="nav-item a-none">
              <a href=""><h3>웹툰</h3></a>
            </li>
            <li class="nav-item a-none">
              <a href=""
                ><h3>더보기 <v-icon>mdi-menu-down</v-icon></h3>
              </a>
            </li>
          </ul>
        </div>
        <div class="group-nav-right a-none">
          <a href=""
            ><h4>
              검색어 필터설정이 필요합니다 <v-icon>mdi-chevron-down</v-icon>
            </h4></a
          >
        </div>
      </section>
    </div>
    <section class="content ">
      <div class="content-left">
        <div class="imgbanner">
          <img src="@/assets/img-main-banner.png" class="width100" alt="" />
        </div>
        <div class="news">
          <div class="newsheader">
            <div class="newsheader-left">
              <a href="" class="margin-r black">연합뉴스 </a>
              <a href="" class=" black"
                ><h4>
                  사흘 만에 또 1천명대…영국발 변이 바이러스까지 엎친데 덮친격
                </h4></a
              >
            </div>
            <div class="newsheader-right">
              <a href="" class="margin-r blue border"><h4>네이버뉴스</h4></a>
              <a href="" class="margin-r black border"><h4>연예</h4></a>
              <a href="" class="margin-r black border "><h4>스포츠</h4></a>
              <a href="" class="black border "><h4>경제</h4></a>
            </div>
          </div>
          <div class="newsmiddle">
            <div class="newsmiddle-left">
              <a href="" class="margin-r black"
                ><v-icon>mdi-format-list-bulleted</v-icon>뉴스스탠드
              </a>
              <a href="" class=" margin-r black">
                구독한언론사
              </a>
              <a href="" class=" black border">
                전체언론사
              </a>
            </div>
            <div class="newsheader-right">
              <a href="" class="margin-r  border"
                ><v-icon>mdi-format-list-bulleted</v-icon></a
              >
              <a href="" class="margin-r border"
                ><v-icon>mdi-view-module</v-icon></a
              >
              <a href="" class=" border"><v-icon>mdi-view-module</v-icon></a>
            </div>
          </div>
        </div>
        <div class="newslist">
          <div class="newslist-row">
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
          </div>
          <div class="newslist-row">
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
          </div>
          <div class="newslist-row">
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
          </div>
          <div class="newslist-row">
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
            <v-col cols="12" sm="2" class="newscard">
              <a href="">뉴스</a>
            </v-col>
          </div>
        </div>
      </div>
      <div class="content-right"></div>
    </section>
  </body>
</template>

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

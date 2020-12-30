<template>
  <div class="body">
    <section class="form-center ">
      <div class="top-left ">
        <ul class="list-nav ">
          <li class="nav-item ">
            <a href=""><h4>네이버를 시작페이지로</h4></a>
          </li>
          <li class="nav-item a-none">
            <a href=""><h4>쥬니어네이버</h4></a>
          </li>
          <li class="nav-item a-none">
            <a href=""><h4>해피빈</h4></a>
          </li>
        </ul>
      </div>
      <div class="top-search">
        <img src="@/assets/logo-naver.png" class="logo-default" alt="logo" />
        <form class="search-input">
          <input
            type="text"
            class="inputbox"
            id="searchkey"
            name="searchkey"
            title="검색"
          />
          <button class="btn-submit"><v-icon>mdi-magnify</v-icon></button>
        </form>
      </div>
    </section>
    <div class="nav-bg">
      <div class="nav-line"></div>
      <section class="group-nav ">
        <div class="group-nav-left">
          <ul class="list-nav">
            <li class="nav-item a-green">
              <a href="" class="primary border">메일</a>
            </li>
            <li class="nav-item a-green">
              <a href="" class="primary border">카페</a>
            </li>
            <li class="nav-item a-green">
              <a href="" class="primary border">블로그</a>
            </li>
            <li class="nav-item a-green">
              <a href="" class="primary border">지식IN</a>
            </li>
            <li class="nav-item a-green">
              <a href="" class="primary border">쇼핑</a>
            </li>
            <li class="nav-item a-green">
              <a href="" class="primary border">PAY</a>
            </li>
            <li class="nav-item a-green">
              <a href="" class="primary border">TV</a>
            </li>
            <li class="nav-item a-none">
              <a href="" class="border">사전</a>
            </li>
            <li class="nav-item a-none">
              <a href="" class="border">뉴스</a>
            </li>
            <li class="nav-item a-none">
              <a href="" class="border">부동산</a>
            </li>
            <li class="nav-item a-none">
              <a href="" class="border">지도</a>
            </li>
            <li class="nav-item a-none">
              <a href="" class="border">영화</a>
            </li>
            <li class="nav-item a-none">
              <a href="" class="border">VIBE</a>
            </li>
            <li class="nav-item a-none">
              <a href="" class="border">책</a>
            </li>
            <li class="nav-item a-none">
              <a href="" class="border">웹툰</a>
            </li>
            <li class="nav-item a-none">
              <a href="" class=" a-line"
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
      <div class="nav-line"></div>
    </div>
    <section class="content ">
      <div class="content-left">
        <div class="imgbanner margin10">
          <img
            src="@/assets/img-main-banner.png"
            class="width100 border"
            alt=""
          />
        </div>
        <div class="newsheader ">
          <div class="newsheader-left">
            <a href="" class="margin-r">연합뉴스 </a>
            <a href="" class=" a-line"
              ><h4>
                사흘 만에 또 1천명대…영국발 변이 바이러스까지 엎친데 덮친격
              </h4></a
            >
          </div>
          <div class="newsheader-right">
            <a href="" class="margin-r blue border none"><h4>네이버뉴스</h4></a>
            <a href="" class="margin-r black border none"><h4>연예</h4></a>
            <a href="" class="margin-r black border none "><h4>스포츠</h4></a>
            <a href="" class="black border none"><h4>경제</h4></a>
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
            <a href="" class="margin-r  border none"
              ><v-icon>mdi-format-list-bulleted</v-icon></a
            >
            <a href="" class="margin-r border none"
              ><v-icon>mdi-view-module</v-icon></a
            >
            <a href="" class=" border none"><v-icon>mdi-view-module</v-icon></a>
          </div>
        </div>
        <div class="newslist-position">
          <div class="newslist">
            <div class="newslist-row">
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
            </div>
            <div class="newslist-row">
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
            </div>
            <div class="newslist-row">
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
            </div>
            <div class="newslist-row">
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
              <a href="" class="none">
                <v-col cols="12" sm="2" class="card" id="id-2"
                  ><img
                    class="img-news"
                    src="@/assets/img-news-logo.png"
                    alt=""
                  /> </v-col
              ></a>
            </div>
          </div>
          <a href="" class="btn-arrow-left">
            <div>
              <v-icon> mdi-chevron-left</v-icon>
            </div>
          </a>

          <a href="" class="btn-arrow-right">
            <div>
              <v-icon> mdi-chevron-right</v-icon>
            </div>
          </a>
        </div>
        <div class="themecast">
          <div class="themecastheader">
            <div class="themecast-left">
              <p class="margin-r">오늘 읽을만한 글</p>
              <h4>주제별로 분류된 다양한 글 모음</h4>
            </div>
            <div class="themecast-right">
              <h4 class="margin-r">1080개의 글</h4>
              <a href="" class=" border"> <h4>관심주제 설정</h4></a>
            </div>
          </div>

          <div class="themecastslist">
            <div class="theme-position">
              <div class="themecastlist-row">
                <v-col cols="12" sm="2" class="card">
                  <a href="" v-on:mouseover="newscardchange">뉴스</a>
                </v-col>
                <v-col cols="12" sm="2" class="card" id="id-2">
                  <a href="">엔터</a>
                </v-col>
                <v-col cols="12" sm="2" class="card">
                  <a href="">스포츠</a>
                </v-col>
                <v-col cols="12" sm="2" class="card">
                  <a href="">푸드</a>
                </v-col>
                <v-col cols="12" sm="2" class="card">
                  <a href="">패션뷰티</a>
                </v-col>
                <v-col cols="12" sm="2" class="card">
                  <a href="">웹툰</a>
                </v-col>
              </div>
              <a href="" class="btn-arrow-left">
                <div>
                  <v-icon> mdi-chevron-left</v-icon>
                </div>
              </a>

              <a href="" class="btn-arrow-right">
                <div>
                  <v-icon> mdi-chevron-right</v-icon>
                </div>
              </a>
            </div>
            <div class="themecastcontents margin10">
              <div class="list-top">
                <a href="" class="themerow margin10 none">
                  <div class="left margin-r">
                    <div class="wrap">
                      <img
                        src="@/assets/img-theme.png"
                        class="theme-img"
                        alt=""
                      />
                    </div>
                  </div>
                  <div class="right">
                    <em class="primary"> 경제M</em>
                    <strong>지혜의 네이버 페이지 따라만들기 도전기</strong>
                    <h4>
                      퍼블리싱이 이토록 어려운것인가 재미가 없는것인가..
                      퍼블리싱이 이토록 어려운것인가 재미가
                      없는것인가..퍼블리싱이 이토록 어려운것인가 재미가
                      없는것인가..퍼블리싱이 이토록 어려운것인가 재미가
                      없는것인가..
                    </h4>

                    <span><h4 class="grey">더패치 / 5일전</h4></span>
                  </div>
                </a>
                <a href="" class="themerow margin10 none">
                  <div class="left margin-r">
                    <div class="wrap">
                      <img
                        src="@/assets/img-theme.png"
                        class="theme-img"
                        alt=""
                      />
                    </div>
                  </div>
                  <div class="right">
                    <em class="primary"> 경제M</em>
                    <strong>지혜의 네이버 페이지 따라만들기 도전기</strong>
                    <h4>
                      퍼블리싱이 이토록 어려운것인가 재미가 없는것인가..
                      퍼블리싱이 이토록 어려운것인가 재미가
                      없는것인가..퍼블리싱이 이토록 어려운것인가 재미가
                      없는것인가..퍼블리싱이 이토록 어려운것인가 재미가
                      없는것인가..
                    </h4>

                    <span><h4 class="grey">더패치 / 5일전</h4></span>
                  </div>
                </a>
                <a href="" class="themerow margin10 none">
                  <div class="left margin-r">
                    <div class="wrap">
                      <img
                        src="@/assets/img-theme.png"
                        class="theme-img"
                        alt=""
                      />
                    </div>
                  </div>
                  <div class="right">
                    <em class="primary"> 경제M</em>
                    <strong>지혜의 네이버 페이지 따라만들기 도전기</strong>
                    <h4>
                      퍼블리싱이 이토록 어려운것인가 재미가 없는것인가..
                      퍼블리싱이 이토록 어려운것인가 재미가
                      없는것인가..퍼블리싱이 이토록 어려운것인가 재미가
                      없는것인가..퍼블리싱이 이토록 어려운것인가 재미가
                      없는것인가..
                    </h4>

                    <span><h4 class="grey">더패치 / 5일전</h4></span>
                  </div>
                </a>
                <a href="" class="themerow margin10 none">
                  <div class="left margin-r">
                    <div class="wrap">
                      <img
                        src="@/assets/img-theme.png"
                        class="theme-img"
                        alt=""
                      />
                    </div>
                  </div>
                  <div class="right">
                    <em class="primary"> 경제M</em>
                    <strong>지혜의 네이버 페이지 따라만들기 도전기</strong>
                    <h4>
                      퍼블리싱이 이토록 어려운것인가 재미가 없는것인가..
                      퍼블리싱이 이토록 어려운것인가 재미가
                      없는것인가..퍼블리싱이 이토록 어려운것인가 재미가
                      없는것인가..퍼블리싱이 이토록 어려운것인가 재미가
                      없는것인가..
                    </h4>

                    <span><h4 class="grey">더패치 / 5일전</h4></span>
                  </div>
                </a>
              </div>
              <div class="line"></div>
              <div class="list-bottom">
                <a href="" class="themerow-b margin-r none">
                  <div class="wrap">
                    <img
                      src="@/assets/img-theme.png"
                      class="theme-img"
                      alt=""
                    />
                  </div>
                  <strong>지혜의 네이버</strong>
                  <span><h4 class="grey">더패치 / 5일전</h4></span>
                </a>
                <a href="" class="themerow-b margin-r none">
                  <div class="wrap">
                    <img
                      src="@/assets/img-theme.png"
                      class="theme-img"
                      alt=""
                    />
                  </div>
                  <strong>지혜의 네이버 페이지 따라만들기..</strong>
                  <span><h4 class="grey">더패치 / 5일전</h4></span>
                </a>
                <a href="" class="themerow-b none">
                  <div class="wrap">
                    <img
                      src="@/assets/img-theme.png"
                      class="theme-img"
                      alt=""
                    />
                  </div>
                  <strong>지혜의 네이버 페이지 따라만들기..</strong>

                  <span><h4 class="grey">더패치 / 5일전</h4></span>
                </a>
              </div>
              <div class="line"></div>
            </div>
          </div>
        </div>
      </div>
      <div class="content-right">
        <div class="loginbox margin10">
          <h4 class="grey">네이버를 더 안전하고 편리하게 이용하세요</h4>
          <a href="" class="btn-login margin10 border none">NAVER LOGIN</a>
          <div class="login-bottom">
            <div class="left">
              <a href="" class="margin-r  a-line">
                <h4><v-icon x-small>mdi-lock</v-icon>아이디</h4></a
              >
              <a href="" class=" a-line"> <h4>비밀번호 찾기</h4></a>
            </div>
            <div class="left">
              <a href="" class=" a-line">
                <h4><v-icon x-small>mdi-account-outline</v-icon>회원가입</h4></a
              >
            </div>
          </div>
        </div>
        <div class="newsheader ">
          <div class="newsheader-left">
            <a href="" class="margin-r black"
              ><h4 class="border badge">
                Live
              </h4>
            </a>
            <a href="" class=" black"
              ><h4>
                저녁방송 메인뉴스보기
              </h4></a
            >
          </div>
          <div class="newsheader-right">
            <a href="" class="margin-r blue border"
              ><v-icon small>mdi-chevron-left</v-icon></a
            >
            <a href="" class=" blue border"
              ><v-icon small>mdi-chevron-right</v-icon></a
            >
          </div>
        </div>
        <div class="imgbanner margin10">
          <img
            src="@/assets/img-sub-banner.png"
            class="width100 border"
            alt=""
          />
        </div>
        <div class=" shoppingtab">
          <div class="newsheader-left">
            <a href="" class="margin-r black"
              ><h3 class="border">
                <v-icon color="var(--primary)">mdi-cart</v-icon>
                트렌드쇼핑
              </h3>
            </a>
          </div>
          <div class="newsheader-right">
            <ul class="list-nav ">
              <li class="nav-item a-none">
                <a href=""><h3 class="">상품</h3></a>
              </li>
              <li class="nav-item a-none">
                <a href=""><h3 class="">쇼핑몰</h3></a>
              </li>
              <li class="nav-item a-none">
                <a href=""><h3 class="">MEN</h3></a>
              </li>
            </ul>
            <!-- <a href="" class="margin-r blue border"
              ><v-icon small>mdi-chevron-left</v-icon></a
            >
            <a href="" class=" blue border"
              ><v-icon small>mdi-chevron-right</v-icon></a
            > -->
          </div>
        </div>
        <div class="shopping">
          <div class="shoppingheader ">
            <div class="flex margin-b">
              <a href="" class="border  a-line"> <h4>G마켓</h4></a>
              <span class="ls"></span>
              <a href="" class=" a-line"> <h4>옥션</h4></a>
              <span class="ls"></span>
              <a href="" class=" a-line"> <h4>11번가</h4></a>
              <span class="ls"></span>
              <a href="" class=" a-line"> <h4>위메프</h4></a>
              <span class="ls"></span>
              <a href="" class=" a-line"> <h4>이마트몰</h4></a>
              <span class="ls"></span>
              <a href="" class=" a-line"> <h4>올리브영</h4></a>
            </div>
            <div class="flex">
              <a href="" class=" a-line"> <h4>티몬</h4></a>
              <span class="ls"></span>
              <a href="" class=" a-line"> <h4>홈플러스</h4></a>
              <span class="ls"></span>
              <a href="" class=" a-line"> <h4>GS샵</h4></a>
              <span class="ls"></span>
              <a href="" class=" a-line"> <h4>롯데i몰</h4></a>
              <span class="ls"></span>
              <a href="" class=" a-line"> <h4>신세계몰</h4></a>
              <span class="ls"></span>
              <a href="" class=" a-line"> <h4>CJmall</h4></a>
            </div>
          </div>
          <div class="shoppingbody">
            <div class="shop-control margin10">
              <div class="margin-r">
                <em>
                  <span class="border">1</span>
                </em>
                <span>/25</span>
              </div>
              <div class="newsheader-right">
                <a href="" class="margin-r none"
                  ><v-icon small>mdi-chevron-left</v-icon></a
                >
                <a href="" class=" none"
                  ><v-icon small>mdi-chevron-right</v-icon></a
                >
              </div>
            </div>
            <div class="list-bottom">
              <a href="" class="themerow-b margin-r  center ">
                <div class="wrap ">
                  <img
                    src="@/assets/img-theme.png"
                    class="shopping-img"
                    alt=""
                  />
                </div>
                <strong><h4>지혜의 네이버</h4></strong>
                <span><h4 class="grey">퍼블리싱 고민 끝!</h4></span>
              </a>
              <a href="" class="themerow-b margin-r  center">
                <div class="wrap">
                  <img
                    src="@/assets/img-theme.png"
                    class="shopping-img"
                    alt=""
                  />
                </div>
                <strong><h4>지혜의 네이버</h4></strong>
                <span><h4 class="grey">퍼블리싱 고민 끝!</h4></span>
              </a>
              <a href="" class="themerow-b  center">
                <div class="wrap">
                  <img
                    src="@/assets/img-theme.png"
                    class="shopping-img"
                    alt=""
                  />
                </div>
                <strong><h4>지혜의 네이버</h4></strong>
                <span><h4 class="grey">퍼블리싱 고민 끝!</h4></span>
              </a>
            </div>
            <div class="list-bottom margin10">
              <a href="" class="themerow-b margin-r none center">
                <div class="wrap ">
                  <img
                    src="@/assets/img-theme.png"
                    class="shopping-img"
                    alt=""
                  />
                </div>
                <strong><h4>지혜의 네이버</h4></strong>
                <span><h4 class="grey">퍼블리싱 고민 끝!</h4></span>
              </a>
              <a href="" class="themerow-b margin-r none center">
                <div class="wrap">
                  <img
                    src="@/assets/img-theme.png"
                    class="shopping-img"
                    alt=""
                  />
                </div>
                <strong><h4>지혜의 네이버</h4></strong>
                <span><h4 class="grey">퍼블리싱 고민 끝!</h4></span>
              </a>
              <a href="" class="themerow-b none center">
                <div class="wrap">
                  <img
                    src="@/assets/img-theme.png"
                    class="shopping-img"
                    alt=""
                  />
                </div>
                <strong><h4>지혜의 네이버</h4></strong>
                <span><h4 class="grey">퍼블리싱 고민 끝!</h4></span>
              </a>
            </div>
            <div class="shop-control-bottom margin10">
              <a href="" class="margin-r none"
                ><v-icon small>mdi-chevron-left</v-icon></a
              >
              <div class="margin-r">
                <em>
                  <span class="border">1</span>
                </em>
                <span>/25</span>
              </div>

              <a href="" class=" none"
                ><v-icon small>mdi-chevron-right</v-icon></a
              >
            </div>
          </div>
        </div>
        <div class="shoppingnews">
          <div class="shoppingheader ">
            <div class="flex margin-b">
              <a href="" class="border"> <h4>G마켓</h4></a>
              <span class="ls"></span>
              <a href=""> <h4>옥션</h4></a>
              <span class="ls"></span>
              <a href=""> <h4>11번가</h4></a>
              <span class="ls"></span>
              <a href=""> <h4>위메프</h4></a>
              <span class="ls"></span>
              <a href=""> <h4>이마트몰</h4></a>
              <span class="ls"></span>
              <a href=""> <h4>올리브영</h4></a>
            </div>
            <div class="flex">
              <a href=""> <h4>티몬</h4></a>
              <span class="ls"></span>
              <a href=""> <h4>홈플러스</h4></a>
              <span class="ls"></span>
              <a href=""> <h4>GS샵</h4></a>
              <span class="ls"></span>
              <a href=""> <h4>롯데i몰</h4></a>
              <span class="ls"></span>
              <a href=""> <h4>신세계몰</h4></a>
              <span class="ls"></span>
              <a href=""> <h4>CJmall</h4></a>
            </div>
          </div>
          <div class="shoppingbody">
            <div class="shop-news-control ">
              <h3>반갑다 쇼핑뉴스</h3>
              <div class="shop-control">
                <div class="margin-r">
                  <em>
                    <span class="border">1</span>
                  </em>
                  <span>/25</span>
                </div>
                <div class="newsheader-right">
                  <a href="" class="margin-r none"
                    ><v-icon small>mdi-chevron-left</v-icon></a
                  >
                  <a href="" class=" none"
                    ><v-icon small>mdi-chevron-right</v-icon></a
                  >
                </div>
              </div>
            </div>
            <div class="list-bottom-news">
              <a href="" class=" flex margin20 a-line">
                <strong class="margin-r"><h4>지혜의 네이버</h4></strong>
                <span><h4 class="grey">퍼블리싱 고민 끝!</h4></span>
              </a>
              <a href="" class=" flex margin20 a-line">
                <strong class="margin-r"><h4>지혜의 네이버</h4></strong>
                <span><h4 class="grey">퍼블리싱 고민 끝!</h4></span>
              </a>
              <a href="" class=" flex margin20 a-line">
                <strong class="margin-r"><h4>지혜의 네이버</h4></strong>
                <span><h4 class="grey">퍼블리싱 고민 끝!</h4></span>
              </a>
              <a href="" class=" flex margin20 a-line">
                <strong class="margin-r"><h4>지혜의 네이버</h4></strong>
                <span><h4 class="grey">퍼블리싱 고민 끝!</h4></span>
              </a>
              <a href="" class=" flex margin20 a-line">
                <strong class="margin-r"><h4>지혜의 네이버</h4></strong>
                <span><h4 class="grey">퍼블리싱 고민 끝!</h4></span>
              </a>
            </div>

            <div class="shop-control-bottom margin10">
              <a href="" class="margin-r none"
                ><v-icon small>mdi-chevron-left</v-icon></a
              >
              <div class="margin-r">
                <em>
                  <span class="border">1</span>
                </em>
                <span>/25</span>
              </div>

              <a href="" class=" none"
                ><v-icon small>mdi-chevron-right</v-icon></a
              >
            </div>
          </div>
        </div>
      </div>
    </section>
    <div class="footer-bg">
      <div class="nav-line"></div>
      <section class="group-footer ">
        <div class="footer-top">
          <a href="" class="themerow  none margin-r">
            <div class="left margin-r">
              <div class="wrap">
                <img src="@/assets/img-theme.png" class="theme-img" alt="" />
              </div>
            </div>
            <div class="right fooger-right">
              <em class="primary ">애플시나몬</em>
              <strong>10주년 이벤트</strong>
              <h4>
                애플시나몬 먹고 네이버 페이 이벤트 참여하세요
              </h4>
            </div>
          </a>
          <a href="" class="themerow  none margin-r">
            <div class="left margin-r">
              <div class="wrap">
                <img src="@/assets/img-theme.png" class="theme-img" alt="" />
              </div>
            </div>
            <div class="right fooger-right">
              <em class="primary ">애플시나몬</em>
              <strong>10주년 이벤트</strong>
              <h4>
                애플시나몬 먹고 네이버 페이 이벤트 참여하세요
              </h4>
            </div>
          </a>

          <a href="" class="themerow  none">
            <div class="left margin-r">
              <div class="wrap">
                <img src="@/assets/img-theme.png" class="theme-img" alt="" />
              </div>
            </div>
            <div class="right fooger-right">
              <em class="primary ">애플시나몬</em>
              <strong>10주년 이벤트</strong>
              <h4>
                애플시나몬 먹고 네이버 페이 이벤트 참여하세요
              </h4>
            </div>
          </a>
        </div>
        <div class="nav-line"></div>
        <div class="themecastheader ">
          <div class="themecast-left">
            <a href="" class=" black border"><h4>공지사항</h4></a>
          </div>
          <div class="themecast-right">
            <a href="" class=" blue border none"
              ><h4>서비스 전체보기 <v-icon>mdi-chevron-right</v-icon></h4></a
            >
          </div>
        </div>
        <div class="nav-line"></div>
        <div class="footer-info">
          <div class="footerheader ">
            <div class="fotter-info-left">
              <div class="flex ">
                <strong class="margin-r"><h4>Creators</h4></strong>
                <a href="" class=" a-line  margin-r"><h4>디자이너</h4></a>
                <a href="" class=" a-line "><h4>퍼블리셔</h4></a>
              </div>
              <div class="flex margin20">
                <strong class="margin-r"><h4>Creators</h4></strong>
                <a href="" class=" a-line  margin-r"><h4>디자이너</h4></a>
                <a href="" class=" a-line "><h4>퍼블리셔</h4></a>
              </div>
              <div class="flex">
                <strong class="margin-r"><h4>Creators</h4></strong>
                <a href="" class=" a-line  margin-r"><h4>디자이너</h4></a>
                <a href="" class=" a-line "><h4>퍼블리셔</h4></a>
              </div>
            </div>

            <div class="themecast-right">
              <a href="" class=" blue border none"><h3>웨일브라우저</h3></a>
            </div>
          </div>
        </div>
        <div class="nav-line"></div>
        <div class="themecastheader ">
          <div class="themecast-left marginb-60">
            <a href="" class=" black border margin-r"><h4>회사소개</h4></a>
            <span class="ls"></span>
            <a href="" class=" black border margin-r"><h4>인재채용</h4></a>
            <span class="ls"></span>
            <a href="" class=" black border margin-r"><h4>제휴제안</h4></a>
            <span class="ls"></span>
            <a href="" class=" black border margin-r"><h4>이용약관</h4></a>
            <span class="ls"></span>
            <a href="" class=" black border margin-r"
              ><h4>개인정보처리방침</h4></a
            >
            <span class="ls"></span>
            <a href="" class=" black border margin-r"
              ><h4>청소년보호정책</h4></a
            >
            <span class="ls"></span>
            <a href="" class=" black border"><h4>지혜</h4></a>
          </div>
          <div class="themecast-right"></div>
        </div>
      </section>
      <div class="nav-line"></div>
    </div>
  </div>
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
<script>
export default {
  methods: {
    newscardchange: function() {
      // return [{ text: "<div>hello</div>" }];
      console.log("test22");
      // ...
    },
  },
};
</script>

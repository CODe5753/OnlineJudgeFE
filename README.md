# OnlineJudge Front End
[![vue](https://img.shields.io/badge/vue-2.5.13-blue.svg?style=flat-square)](https://github.com/vuejs/vue)
[![vuex](https://img.shields.io/badge/vuex-3.0.1-blue.svg?style=flat-square)](https://vuex.vuejs.org/)
[![echarts](https://img.shields.io/badge/echarts-3.8.3-blue.svg?style=flat-square)](https://github.com/ecomfe/echarts)
[![iview](https://img.shields.io/badge/iview-2.8.0-blue.svg?style=flat-square)](https://github.com/iview/iview)
[![element-ui](https://img.shields.io/badge/element-2.0.9-blue.svg?style=flat-square)](https://github.com/ElemeFE/element)
[![Build Status](https://travis-ci.org/QingdaoU/OnlineJudgeFE.svg?branch=master)](https://travis-ci.org/QingdaoU/OnlineJudgeFE)
![95%](https://progress-bar.dev/85?title=한글화)
>### A multiple pages app built for OnlineJudge. [Demo](https://qduoj.com)

## 한글화 진행중
FrontEnd 한글화 진행중입니다.
[작동중인 페이지로 이동](http://inje-oj.com)

## 동작 방식
기존의 Docker를 동작시키고 해당 FrontEnd를 TARGET으로 BackEnd를 연결시켜 줍니다.  
FrontEnd는 수정된 상태로 표시되고, BackEnd는 기존과 동일하게 동작합니다.  

## Get Started
nodejs **v8.12.0** 설치 필요.

### Linux

```bash
npm install
# we use webpack DllReference to decrease the build time,
# this command only needs execute once unless you upgrade the package in build/webpack.dll.conf.js
export NODE_ENV=development 
npm run build:dll

# the dev-server will set proxy table to your backend
export TARGET=http://Your-backend

# serve with hot reload at localhost:8080
npm run dev
```

## 스크린샷

[Check here.](https://github.com/QingdaoU/OnlineJudge)

## 브라우저 지원

Internet Explorer 10+, Chrome

## 라이센스

[MIT](http://opensource.org/licenses/MIT)

# OnlineJudge Front End
[![vue](https://img.shields.io/badge/vue-2.5.13-blue.svg?style=flat-square)](https://github.com/vuejs/vue)
[![vuex](https://img.shields.io/badge/vuex-3.0.1-blue.svg?style=flat-square)](https://vuex.vuejs.org/)
[![echarts](https://img.shields.io/badge/echarts-3.8.3-blue.svg?style=flat-square)](https://github.com/ecomfe/echarts)
[![iview](https://img.shields.io/badge/iview-2.8.0-blue.svg?style=flat-square)](https://github.com/iview/iview)
[![element-ui](https://img.shields.io/badge/element-2.0.9-blue.svg?style=flat-square)](https://github.com/ElemeFE/element)
[![Build Status](https://travis-ci.org/QingdaoU/OnlineJudgeFE.svg?branch=master)](https://travis-ci.org/QingdaoU/OnlineJudgeFE)
>### [Demo](http://inje-oj.com)

## 개발 환경
Env : `AWS EC2 t2.small`  
OS : `Ubuntu 18.04`  
Nodejs : `v8.17.0`  
**해당 Frontend는 Backend 서버와 분리된 환경입니다.**


## HTTPS
export TARGET proxy를 이용하여 FE를 구성하였습니다.
빠른 시일 내 HTTPS를 설정할 계획입니다.

## 한글화
기존에 없었던 `ko-KR` locale을 생성 및 설정했습니다.

## Get Started
nodejs **v8.12.0** ~ **v8.17.0** 설치 필요.

### Linux
```bash
npm install

export NODE_ENV=development 
npm run build:dll

export TARGET=http://Backend URL

npm run dev
```
## LICENSE
[MIT](http://opensource.org/licenses/MIT)

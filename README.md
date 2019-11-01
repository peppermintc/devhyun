# Devhyun

![logo](https://raw.githubusercontent.com/opzyra/devhyun/master/public/images/favicon.png)

[https://devhyun.com](https://devhyun.com)

**데브현은 개인 브랜딩, 개발 블로그, 자기관리 기능이 포함된 웹 애플리케이션입니다.**  
AWS EC2에 배포하였으며 자세한 기술 스택은 아래를 참고해주세요.

## 기술스택

### Client

- Handlesbar.js
- JQuery
- CSS

### Server

- Express
- Knex.js
- fxjs
- webpack
- MySQL

## 개발 포인트

- [데코레이터 패턴을 활용한 Express Router 에러 핸들링 및 트랜잭션 관리](https://github.com/opzyra/devhyun/blob/master/src/core/tx.js)
- [Browser에서 ES6 사용을 위한 Webpack 도입 및 스크립트 모듈화](https://github.com/opzyra/devhyun/blob/master/src/script/index.js)
- [Express의 미들웨어를 활용한 권한체크 및 파라미터 유효성 검사](https://github.com/opzyra/devhyun/blob/master/src/lib/validator.js)
- [Jsdoc를 통한 쿼리 문서화](https://github.com/opzyra/devhyun/blob/master/src/sql/Application.js)

## 연관 포스트

- [프로젝트 데브현](https://devhyun.com/blog/post/11)
- [Express 미들웨어를 활용한 에러 처리](https://devhyun.com/blog/post/6)
- [Express REST API 유효성 검사](https://devhyun.com/blog/post/7)

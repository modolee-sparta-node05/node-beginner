# Node.js 입문주차 과제

- 간단히 상품 CRUD를 구현해 보는 프로젝트
- 에러 처리 미들웨어 추가
- Joi를 이용한 유효성 검증 추가

# 실행 방법

1. `.env` 파일을 생성하여, 환경변수를 추가한다.
2. `yarn` 명령으로 프로젝트에 필요한 패키지를 설치한다.
3. `yarn start`명령으로 서버를 실행한다. (개발 시에는 `yarn dev`)

# 환경변수

## 설명

- SERVER_PORT: 서버가 실행 될 포트
- MONGODB_URL: MongoDB가 서비스되고 있는 URL
- MONGODB_NAME: MongoDB 데이터베이스 이름

## 예시

```bash
SERVER_PORT=3000
MONGODB_URL=mongodb+srv://admin:password@cluster0.qwer.mongodb.net/?retryWrites=true&w=majority
MONGODB_NAME=node_beginner
```

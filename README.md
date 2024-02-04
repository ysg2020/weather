# 날씨 일기 시스템 API
오픈 API를 통해 가져온 날씨와 함께 일기를 작성하는 프로젝트

[날씨 일기 API 개발시 얻은 인사이트](https://tobe-lv100.tistory.com/14)

## 기술 스택
- Spring boot , java
- MySql, Jpa
- swagger

## API
- 일기 작성 API
- 일기 삭제 API
- 일기 조회 API
- 일기 수정 API
---

### 일기 작성 API
- POST /create/diary
  - 오픈 API를 통해 가져온 날씨 데이터와 함께 일기 저장

### 일기 삭제 API
- DELETE /delete/diary 
  - 특정 날짜에 저장한 일기 모두 삭제
  
### 일기 조회 API
- GET /read/diary
  - 특정 날짜에 작성한 일기 조회

- GET /read/diaries 
  - 특정 기간안에 작성한 일기 조회

### 일기 수정 API
- PUT /update/diary
  - 특정 날짜에 작성한 첫번째 일기 수정

  

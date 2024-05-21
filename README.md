# 냥가왈부 백엔드 

SpringBoot 3.2.5 버전 사용

- spring boot 기반
- JPA, QueryDsl, Mysql 로 DB 관리
- API 서버 구현

### 브랜치 규칙

1. main : 초기 프로젝트 기본 설정 -> 오류, 프로젝트 롤백 시 사용할 스냅샷
2. dev : 각자의 브랜치에서 병합해서 진행할 최종 개발 산출물 브랜치
3. 각자 이름 브랜치 : 개인의 작업물을 먼저 이곳에 올리고 그다음에 dev로 풀 리퀘스트 Go

### 커밋메세지 규칙
~~~
  < type >: 제목       //헤더필수
                      //빈행으로 구분함
  본문

~~~
|타입이름|내용
|------|---|
feat|	새로운 기능에 대한 커밋
fix|	버그 수정에 대한 커밋
connect|	외부 연결 (CI/CD 연결하기) 
question|   질문
refactor|	코드 리팩토링에 대한 커밋
test|	테스트 코드 수정에 대한 커밋

EX.
 ~~~
 feat: 사용자 프로필 페이지 추가
 
 - 사용자 프로필 페이지 및 라우팅 구현
 - 프로필 정보를 보여주는 프로필 카드 컴포넌트 구현
 - 프로필 수정 기능 구현
 ~~~

# Blog Project
#### 스프링부트 게시판 프로젝트

</br></br></br>

### 순서
[1. 개요](#개요) <br/>
[2. 사용된 기술](#사용된-기술) <br/>
[3. 요구사항 분석](#요구사항-분석) <br/>
[4. 화면 및 API 명세서](#화면-및-API-명세서) <br/>
[5. 실행결과](#실행결과) <br/>
[6. 회고](#회고)

</br>

***

</br>

## 개요
✔ 프로젝트 명 : Blog Project
</br>
✔ 개발 인원 : 1명
</br>
✔ 프로젝트 기간 : 23년 10월 23일 ~ 11월 7일 (2주) 
</br>
✔ 개발 목적 : Spring Boot, OAuth2, Security, DBMS 실습을 위한 게시판 웹사이트 프로젝트
</br>
✔ 주요 기능 <br/>
&emsp;&emsp;-사용자 : Spring Security, OAuth2 소셜로그인, 회원가입, 회원탈퇴, 유효성 검사 및 중복 검사<br/>
&emsp;&emsp;-블로그 : 글 작성, 수정, 삭제 
</br></br></br>


## 사용된 기술
✔ 개발 환경 : Window 10, IntelliJ IDEA, VScode
</br>
✔ 개발 언어 :  Java(Spring Boot), React(JavaScript)
</br>
✔ 데이터베이스 : MySQL, PostgreSQL
</br></br></br>

## 요구사항 분석
✔ 로그인 
+ 가입되지 않은 아이디로 로그인 시도할 때 "존재하지 않는 아이디입니다.
+ 아이디와 비밀번호 일치하지 않을 때 "ID와 비밀번호를 다시 확인해주세요"
+ 로그인 성공 시 "로그인 성공", JWT 발급 -> 홈으로 이동
</br>

✔ 회원가입
+ 회원가입 성공 시 "회원가입 성공", DB에 user 데이터 삽입 -> 로그인 화면으로 이동
</br>

✔ 블로그 게시판 작성 
+ 글 작성, 수정, 삭제 시 DB에 변경사항 적용 
</br></br></br>



## 화면 및 API 명세서

<img src="https://github.com/recordhyo/RECL/assets/126046238/18dc871e-6a99-489a-9084-5f47f2cad8b4"/>

</br></br></br>



## 실행결과
### ✔ 실행화면
**회원가입**

https://github.com/recordhyo/blogtoyproject/assets/126046238/8a3d82d6-c0a3-4ca6-add2-d40816045388

<br/>

**글 수정**

https://github.com/recordhyo/blogtoyproject/assets/126046238/143c8982-3f61-405d-ab60-a3a199c02bd4

<p style="display:inline-block;">수정 전</p>
<img src="https://github.com/recordhyo/RECL/assets/126046238/991e6e9e-b687-4d68-90e7-a35bfdf17610"/>
<p style="display:inline-block;">수정 후</p>
<img src="https://github.com/recordhyo/RECL/assets/126046238/27b2d010-87ed-4bc7-9494-1f794dbc5b04"/>


<br/><br/>


**글 삭제**

https://github.com/recordhyo/blogtoyproject/assets/126046238/0c8132be-fc4c-4cec-9bde-b1a4c6bd800b

<p style="display:inline-block;">삭제 후</p>
<img src="https://github.com/recordhyo/RECL/assets/126046238/6f5435a1-0524-44bc-9edf-007121e1d437"/>

<br/>

</br></br></br>

## 회고
+ 스프링부트의 순환 참조 에러갈 발생해 빈 의존 주입에 대해 학습할 수 있었습니다.
+ 웹 계층구조와 MVC의 관계를 학습할 수 있었습니다.
+ RESTful API의 특징과 원칙을 배울 수 있었고 API 명세서 및 문서화의 필요성을 느꼈습니다.
+ 댓글기능과 배포까지 진행하고 싶습니다. 





# 🚀 Spring-Vue-Board: BoardSimple
BoardSimple은 간단한 CRUD 기능을 갖춘 게시판 포털 서비스입니다. 사용자(SPA)와 관리자(MPA) 2가지 버전으로 제작되었습니다.

## 🏠 메인 화면
| 사용자 게시판 | 관리자 게시판 |
|---------|---------|
|![image](https://github.com/gumgu/Spring-Vue-Board/assets/87007010/28495501-7239-41b4-b31b-b053f1fd22de)|![image](https://github.com/gumgu/Spring-Vue-Board/assets/87007010/0b6ee6c2-f597-4a68-864b-e9555450b430)|

## 📑 프로젝트 소개
### 사용자 게시판
Springboot와 Vue.js를 이용하여 RestfulAPI 기반 SPA 방식으로 제작되었습니다.
- **회원(사용자)**: JWT와 Servlet Filter를 통한 회원가입 및 로그인, 아이디 중복 확인.
- **게시판**: 기본 CRUD, Validation(검증), 검색 및 페이징, 조회수.
- **문의글**: 기본 CRUD, privacy(작성자만 조회 가능), 자신의 문의글만 조회.
- **파일**: 파일 업로드, 조회, 다운로드.
- **댓글**: 기본 CRUD.

### 관리자 게시판
Springboot와 thymeleaf를 이용하여 MVC2 패턴 기반 MPA 방식으로 제작되었습니다.
- **회원(관리자)**: session과 Spring Interceptor를 통한 회원가입 및 로그인.
- **게시판**: 모든 게시글 수정 및 삭제, Validation(검증), 검색 및 페이징, 조회수.
- **문의글**: 모든 게시글 수정 조회 및 삭제, 자신의 문의글만 조회.
- **파일**: 파일 업로드, 조회, 다운로드, 삭제
- **댓글**: 기본 CRUD.

## 💡 저는 이 프로젝트를 통해서...
- 

## 🌐 플랫폼
Web

## 🧑‍💻 개발 인원
1명 **(개인 프로젝트)**

## 🗓️ 개발 기간
2023.07.01 ~ 2023.08.29 (2개월)

## ⚙️ 개발 환경
- 언어: Java(JDK 1.8), HTML/CSS, JavaScript
- 프레임워크: Spring Framework(2.7.4), MyBatis(2.3.10), Thymeleaf
- DB: MySQL(8.0)
- IDE: IntelliJ IDEA 2023
  
## 💾 ERD
![adminBoard (7)](https://github.com/gumgu/Spring-Vue-Board/assets/87007010/8b9d5aa2-dc19-4f4d-9761-fa5c6cb09679)

* * *
## 🌟 주요 기능

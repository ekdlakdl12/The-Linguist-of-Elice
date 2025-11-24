# 📚 프로젝트 소개  
   - 본 프로젝트는 엘리스 AI 트랙 11기 첫 번째 프로젝트로, 2팀에서 개발한 포트폴리오 공유사이트 **'Valley-Tales'** 입니다.    
  
  
# 프로젝트 기간  
  -2024년 6월 17일(월) ~ 2023년 6월 28일(금), 약 2주 간  
  
  
# 프로젝트 목적
  -포트폴리오를 저장하고 공유하는 사이트  
  
  
# 기술 스택
**Front-end** : <img alt="Html" src ="https://img.shields.io/badge/HTML5-E34F26.svg?&style=for-the-badge&logo=HTML5&logoColor=white"/> <img alt="Css" src ="https://img.shields.io/badge/CSS3-1572B6.svg?&style=for-the-badge&logo=CSS3&logoColor=white"/> <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=black" style="max-width: 100%;">  
**Back-end**  : <img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white"> <img src="https://img.shields.io/badge/mongoDB-47A248?style=for-the-badge&logo=MongoDB&logoColor=white">  <img src="https://img.shields.io/badge/express.js-000000?style=for-the-badge&logo=express&logoColor=white"/> 
  
# 형상관리  
  <img src="https://img.shields.io/badge/gitlab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=black"/>  
  
# 팀 멤버
| 담당 업무 | 이름 |
| ------ | ------ |
| **Front-end** | 황솜귤(팀장), 김민지, 임형선 |
| **Back-end** | 김재영, 최준영 |
  
<br/>
  
# 📚 서비스 기능  
User(사용자 관련 기능)  
  
# 1️⃣ 인증

  - 회원가입/탈퇴
  - 이메일 인증
  - 로그인/로그아웃
  - 비밀번호 변경

# 2️⃣ 유저 개인 페이지
 
-다른 유저의 개인 페이지는 조회만 가능  
1. 유저 프로필  
  - 프로필 변경
    - 프로필 사진 url  
    - 이름  
    - 설명  

2. 학력
  - CRUD
  
3. 수상 이력
  - CRUD
  
4. 포트폴리오
  - CRUD
  
5. 자격증
  - CRUD
  
# :three: 유저네트워크 페이지
  - 모든 유저 카드
  
# 📚 서비스 관련  
## 테스트 계정  
ID : test@test.com  
PW : test  

# API 명세서  
→ <a href="https://docs.google.com/spreadsheets/d/1zf1ba67KJeYdKVzmxcpR9E7Rf_9xZpqaGcunBZAFwtM/edit?gid=0#gid=0">API 명세서 바로가기</a>
  
# 🏛️ 프로젝트 아키텍처 및 구조

## 1. 데이터베이스 설계 (ERD)

<div align="center">
    
  <img src="assets/ERD.png" alt="프로젝트 엔티티 관계 다이어그램" width="650" />
  
  <br>
  
  <p>사용자(User)를 중심으로 교육, 자격증, 프로젝트, 수상 정보가 1:N 관계로 구성됩니다.</p>
</div>  

## 2. 주요 화면 구성 및 흐름 (Wireframe)

<div align="center">
  
  <img src="assets/화면구성.webp" alt="프로젝트 주요 화면 및 페이지 흐름도" width="850" />
  
  <br>
  
  <p>공통 페이지, 로그인/회원가입, 사용자 페이지(users), 개인 페이지(mypage)로 구성된 화면 흐름도입니다.</p>
</div>  

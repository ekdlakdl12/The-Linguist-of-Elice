<h1 align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=24a19c&height=500&section=header&text=Valley-Tales&fontSize=80&fontColor=ffffff&fontAlign=center&desc=엘리스%20AI%20트랙%2011기%20포트폴리오%20저장%20및%20공유%20플랫폼&descAlign=center&descPosition=80&descSize=25" alt="Valley-Tales Header">
</h1>
<div align="center">

<p align="center">
    <img src="https://img.shields.io/badge/STATUS-COMPLETED-3e913d?style=for-the-badge"/> 
    <img src="https://img.shields.io/badge/FOCUS-PORTFOLIO%20SHARING%20PLATFORM-0077b6?style=for-the-badge"/>
    <img src="https://img.shields.io/badge/DURATION-2%20WEEKS%20PROJECT-e76f51?style=for-the-badge"/>
</p>

</div>
<br>

---

> 엘리스 AI 트랙 11기 첫 번째 프로젝트로, 2팀에서 개발한 포트폴리오 저장 및 공유 서비스입니다.

---

## 🚀 프로젝트 개요

| 구분 | 내용 |
| :--- | :--- |
| **프로젝트명** | Valley-Tales |
| **개발 목적** | 개인의 포트폴리오를 효율적으로 저장하고 다른 사용자와 공유하는 플랫폼 구축 |
| **개발 기간** | 2024년 6월 17일(월) ~ 2024년 6월 28일(금) (약 2주) |
| **팀 구성** | 엘리스 AI 트랙 11기 2팀 |
| **API 명세서** | [API 명세서 바로가기](https://docs.google.com/spreadsheets/d/1zf1ba67KJeYdKVzmxcpR9E7Rf_9xZpqaGcunBZAFwtM/edit?gid=0#gid=0) |

---

## 🛠️ 기술 스택 (Tech Stack)

### Front-end
<img alt="Html" src ="https://img.shields.io/badge/HTML5-E34F26.svg?&style=for-the-badge&logo=HTML5&logoColor=white"/>
<img alt="Css" src ="https://img.shields.io/badge/CSS3-1572B6.svg?&style=for-the-badge&logo=CSS3&logoColor=white"/>
<img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=black" style="max-width: 100%;">

### Back-end
<img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">
<img src="https://img.shields.io/badge/express.js-000000?style=for-the-badge&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/mongoDB-47A248?style=for-the-badge&logo=MongoDB&logoColor=white">

### 형상 관리 (Version Control)
<img src="https://img.shields.io/badge/gitlab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=black"/>

---

## 🧑‍💻 팀 멤버 (Team Members)

| 담당 업무 | 이름 | 역할 |
| :---: | :---: | :--- |
| **Front-end** | 황솜귤 | 팀장, 프론트엔드 개발 |
| **Front-end** | 김민지 | 프론트엔드 개발 |
| **Front-end** | 임형선 | 프론트엔드 개발 |
| **Back-end** | 김재영 | 백엔드 개발, 데이터베이스 관리 |
| **Back-end** | 최준영 | 백엔드 개발, API 설계 |

---

## 📌 주요 서비스 기능 (Core Features)

### 1. 인증 (Authentication)
* **회원 관리:** 회원가입 및 탈퇴 기능 제공
* **계정 보안:** 이메일 인증을 통한 가입 확인
* **세션 관리:** 로그인 및 로그아웃 처리
* **비밀번호 관리:** 비밀번호 변경 기능

### 2. 유저 개인 페이지 (My Page & User Profile)
> 개인 페이지는 **수정(CRUD)**이 가능하며, 타인의 페이지는 **조회**만 가능합니다.

* **유저 프로필 관리:**
    * 프로필 사진(URL) 등록/변경
    * 이름 및 설명 변경
* **포트폴리오 항목 관리 (CRUD)**
    * 학력 정보
    * 수상 이력
    * 포트폴리오
    * 자격증 정보

### 3. 유저 네트워크 페이지 (Network)
* **모든 유저 카드 조회:** 플랫폼 내 모든 사용자들의 포트폴리오를 한 눈에 볼 수 있는 페이지 제공

---

## 🏛️ 프로젝트 아키텍처 및 구조

### 1. 데이터베이스 설계 (ERD: Entity-Relationship Diagram)

<div align="center">
  
  <img width="431" height="749" alt="ERD" src="https://github.com/user-attachments/assets/e81296c7-b004-4075-8a75-341273e6a63e" />
  
  <br>
  
  <p>사용자(<code>User</code>)를 중심으로 교육, 자격증, 프로젝트, 수상 정보가 1:N 관계로 구성되는 구조입니다.</p>
</div>

### 2. 주요 화면 구성 및 흐름 (Wireframe)

<div align="center">
  
   <img alt="화면구성" src="https://github.com/user-attachments/assets/1599c39b-0540-4e74-892d-6fc0c537daa3" />
  
  <br>
  
  <p>공통 페이지, 로그인/회원가입, 사용자 목록 페이지(users), 개인 페이지(mypage)로 구성된 화면 흐름도입니다.</p>
</div>

---

## 🔑 테스트 계정 정보 (Demo Account)

| 항목 | 정보 |
| :---: | :---: |
| **ID (Email)** | `test@test.com` |
| **PW (Password)** | `test` |

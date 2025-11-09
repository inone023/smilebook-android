# 📱 SmileBook Android App

**스마트 도서관 시스템의 모바일 클라이언트 애플리케이션**입니다.  
Spring Boot API 서버와 통신하여 도서 검색, 예약, 대출 연장, 회원 관리 및 관리자 기능을 제공합니다.

---

## ⚙️ Tech Stack

| 분야 | 기술 |
|------|------|
| Language | Java |
| Framework | Android SDK |
| Network | Retrofit2 |
| Push | Firebase Cloud Messaging |
| Design | XML, Figma |
| IDE | Android Studio |

---

## 🧩 주요 기능

### 👤 회원 기능
- 회원가입 / 로그인  
- 내 정보 조회 및 수정  
- 도서 검색 / 예약 / 대출 연장  

### 🔔 알림 기능
- 대출/반납/이용정지 시 FCM 푸시 알림 수신  

### 🧭 관리자 기능
- 관리자 인증  
- 회원 목록 조회  
- 경고 및 이용정지 처리  

---

## 🔗 API 연동 구조

Android App ⇄ SmileBook API Server ⇄ AWS RDS (MySQL)

---

## 📸 주요 화면

| 기능          | 예시 화면                                 |
| ----------- | ------------------------------------- |
| 회원가입 화면     | ![signup](signup.png)             |
| 로그인 화면      | ![login](login.png)               |
| 앱 메인화면      | ![main](main.png)                 |
| 전체 도서 목록    | ![booklist](booklist.png)         |
| 찜 도서 목록     | ![wishlist](wishlist.png)         |
| 검색어 입력      | ![searchinput](searchinput.png)   |
| 검색 결과 표시    | ![searchresult](searchresult.png) |
| 도서 위치 화면    | ![booklocation](booklocation.png) |
| 도서 정보 화면    | ![bookinfo](img/bookinfo.png)         |
| 내 도서 목록     | ![mybooks](img/mybooks.png)           |
| 대출 연장 화면    | ![extendloan](img/extendloan.png)     |
| 관리자 인증 화면   | ![adminauth](img/adminauth.png)       |
| 도서 등록 화면    | ![bookadd](img/bookadd.png)           |
| 회원 목록 화면    | ![userlist](img/userlist.png)         |
| 회원 상세 정보 화면 | ![userdetail](img/userdetail.png)     |

---

## 📈 결과

- REST API 통신 안정화 (Retrofit + Gson Converter)  
- FCM 기반 푸시 알림 정상 수신 및 UI 표시  
- 직관적인 UI/UX 설계 및 구현 (Figma 기반)

---

## 🧾 관련 프로젝트
- [🌐 SmileBook-API (Server)](https://github.com/yourusername/smilebook-api)
- [🔌 SmileBook-Arduino (IoT)](https://github.com/yourusername/smilebook-arduino)

---

© 2024 SmileBook Team. All rights reserved.

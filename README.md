# 🎵&nbsp;&nbsp;Whale - 음악 스트리밍 및 커뮤니티 서비스 웹사이트
<br>

Spotify API를 활용하여 **음악 스트리밍 및 커뮤니티** 기능을 제공하는 웹사이트입니다.<br>
로그인/회원가입, 음악 스트리밍, 피드/커뮤니티, 메시지/프로필, 환경설정, 관리자 등의 기능을 포함하며,<br>
**두 개의 탭을 양쪽에 배치하여 스트리밍을 즐기면서도 커뮤니티 기능을 원활히 사용할 수 있도록 설계**했습니다.<br><br>
백엔드는 **Java(Spring) & Node.js**, 프론트엔드는 **Vue.js & JSP**,<br>
데이터는 **Spotify API 및 Oracle DB**를 활용하여 구성되었습니다.<br><br>

## 📌&nbsp;&nbsp;프로젝트 목표
- **Spotify API 활용** : 외부 데이터를 연동하고 가공하는 경험을 쌓음<br>
- **커뮤니티 및 SNS 기능 구축** : 자체 DB를 통해 사용자 간 음악 관련 소통 기능(게시판, 피드, 메시지) 개발<br>
- **이중 서버 환경 적용** : Node.js & Spring 병행 운영을 통한 확장성 확보<br>
- **SSR과 CSR의 기술 비교** : SSR(Spring) vs CSR(Node.js + Vue.js) 구조를 학습 목적에 맞게 적용<br><br>

## 📌&nbsp;&nbsp;프로젝트 개요
- **진행 기간** : 2024.10.15 ~ 2024.11.21 (총 38일)<br>
- **팀원 구성** : 풀스택 5명<br>
- **사용 기술** : Java, Javascript, Vue.js, Spring Framework, Node.js, Oracle, MyBatis<br><br>

## 📌&nbsp;&nbsp;담당 역할 및 구현 기능
### 1️⃣&nbsp;&nbsp;**메인 화면 개발** (100%)
- 7가지 주요 기능(음악 스트리밍, 피드, 메시지, 프로필, 환경설정, 관리자, 검색) 동시 배치<br>
- Spotify 음악 플레이어 : 음악 스트리밍, 피드, 메시지, 프로필 등에서 음악을 재생할 경우, 메인 화면 플레이어에서 연동하여 재생 처리 및 플레이어 기능 구현<br>
- 알림 시스템 : 좋아요, 댓글, 팔로우, 관리자 알림 및 WebSocket을 활용한 실시간 메시지 알림 처리<br><br>
![Image](https://github.com/user-attachments/assets/134f7f8f-be68-4713-80d5-88d689b69f62)<br><br>
![Image](https://github.com/user-attachments/assets/ddc1e7d5-d117-47ac-a525-ba21b96918ae)

### 2️⃣&nbsp;&nbsp;**음악 스트리밍 기능 개발** (60%)
- 앨범, 아티스트, 트랙, 플레이리스트 상세 페이지 구현<br>
- Spotify API를 활용한 음악 검색 및 정보 제공<br>
- 트랙 좋아요 기능 구현 (자체 DB 활용)<br><br>

### 3️⃣&nbsp;&nbsp;**검색 기능 구현** (50%)
- 유저, 피드, 커뮤니티 글 및 댓글 검색 기능 개발<br>

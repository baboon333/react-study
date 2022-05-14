# react-study

# 🍻 야술먹자

<img src="/app/메인10.jpg" width="60%" height="60%">

전국 주류 및 주점 검색부터 술모임까지 한 번에!  
애주가들을 위한 상세한 주류 정보 및 판매 주점 정보 제공서비스,
술모임서비스, 채팅서비스등을 제공하는 서비스입니다.

## 바로가기

- 📗 [개요](#-overview)

- 💻 [주요기능 및 화면](#-view)

- 🌈 [노션 링크](https://deadpan-fireplace-ddb.notion.site/Debugger-5574baffadcb4b0ba47de81f5470267a)

## 📗 OverView

- 개발 기간 : 2개월
  - 분석 및 설계 : 2022/02/23 ~ 2022/03/20
  - 구현 : 2022/03/21 ~ 2022/05/01
- 총 개발 인원 : 6명
- 개발 스택
  - Laguage : Java
  - Back-end : Spring Boot / MyBatis / Apache Tomcat
  - Front-end : HTML / BootStrap / CSS / JavaScript / jQuery / Ajax
  - Database : MariaDB / MongoDB
  - Build tool : Gradle
  - VCS tool : GitHub
  - IDE : Eclipse
  - Editor : Atom, VS Code
  - etc. tool : DBeaver, eXERD, Figma
  - Open API : Kakao, Summernote

## 💻 View

### 메인

- 주요 기능인 주종, 주점, 커뮤니티, 우리지금만나로 이동할 수 있습니다.  
  <img src="/app/메인10.jpg" width="55%" height="55%">

### 주류 리스트

- 등록된 주류를 전체 및 카테고리별로 분류하여 페이징처리 후 주류 리스트 페이지에 출력합니다.
  <img src="/app/주점리스트.jpg" width="60%" height="60%">  


### 주류 상세

- 제조사, 소재지, 용량 등 등록된 주류의 상세정보와 그 주류를 판매하는 주점의
  리스트가 나오고 그 주점의 위치 정보를 지도를 통해 확인할 수 있습니다.
  <img src="/app/주점상세.jpg" width="60%" height="60%">  
  <img src="/app/리뷰.jpg" width="60%" height="60%">

### 주점 리스트

- 카테고리별로 주점들을 확인할 수 있고 주점의 위치 정보가 지도에 표시되며 사용자와 주점간의 거리를 확인할 수 있습니다.
  <img src="/app/주점리스트수정.jpg" width="60%" height="60%">

### 주점 상세

- 주점리스트에서 주점을 선택하면 상세정보와 그 주점이 판매하는 주류정보, 안주정보, 해당 주점의 리뷰를 확인 할 수 있고 공유하기 버튼으로 카카오톡 공유가 가능합니다.
  <img src="/app/주점상세1.jpg" width="60%" height="60%">
  <img src="/app/채팅.jpg" width="60%" height="60%">

### 모임 리스트

-

<img src="/app/우리지금만나리스트.jpg" width="60%" height="60%"> 
<img src="/app/모임지도.jpg" width="60%" height="60%">

### 모임 상세

<img src="/app/모임상세.jpg" width="60%" height="60%"> 
<img src="/app/모임글쓰기.jpg" width="60%" height="60%">

### 모임 채팅

- 아이디를 정하여 해당 아이디를 가진 사용자에게 메시지를 보낼 수 있습니다.
  <img src="/app/채팅.jpg" width="60%" height="60%">

### 관리자 페이지

- 회원/주점관리

  - 등록된 회원/주점현황을 확인할 수 있고, 검색(이름 등)을 통해 회원/주점 검색이 가능합니다.
  - 신고내역을 확인 후 특정 회원/주점에게 제재를 가할 수 있고, 강제탈퇴/삭제를 시킬 수 있습니다.
  - 탈퇴 및 삭제가 된 회원/주점은 데이터베이스에 정보는 남아있지만, 로그인은 할 수 없습니다.

- 주류관리

  - 등록된 주류현황을 확인할 수 있고, 주류정보를 등록할 수 있습니다.
  - 주류의 정보를 수정, 삭제도 가능하고, 검색(주류명, 주종)을 통해 주류 검색이 가능합니다.

- 게시글 신고관리
  - 등록된 신고접수현황(전체, 처리완료)을 확인할 수 있고, 접수된 신고의 내용을 확인한 후 게시글을 제재하거나 삭제할 수 있습니다.

<img src="/app/관리자리스트.jpg" width="60%" height="60%">
<img src="/app/관리자등록.jpg" width="60%" height="60%">

<h1 align="center">
  <br>
  <img src="https://github.com/user-attachments/assets/d971e139-2f93-463b-8eba-e7fc7c5a71da" alt="WC logo" width="200">
  <p>
  <p>
  Weather Claus
  </p>
</h1>

<h4 align="center">날씨가 어려운 이들을 위한 사이트, ${\textsf{\color{#adbcc9}웨더클로스}}$입니다</h4> <br>

![ws_video_1](https://github.com/user-attachments/assets/e5cdc26e-df71-4f3b-b9d6-45d72f18105d)

<br/>

## 프로젝트 소개
웨더클로스 프로젝트는 날씨에 따른 옷차림을 추천해주는 웹사이트입니다. <br>
검색이나 위치 동의를 통해 원하는 지역의 날씨를 확인하고 옷차림 추천을 받아보세요 <p>
&ensp; ${\textsf{\color{#adbcc9}p.s. 웨더클로스 멤버가 되어 팀 웨더클로스가 준비한 특별한 기능을 만나보세요 !}}$ 🎁 <p>
웨더클로스 사이트 : https://weather-claus.netlify.app/
<br>
<br>
  
## 개발 기간과 팀 웨더클로스
개발 기간 : 2024.10.04 - 11.13 <br>
- 팀 웨더클로스 소개

| `FE`  | `FE`  | `BE`  |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/c1451f00-73f1-4db3-8f41-d84a73194ce0" width="140"> | <img src="https://github.com/user-attachments/assets/3df26c4d-1d57-4a05-bd05-a02c5fb5cc7c" width="150"> | <img src="https://github.com/user-attachments/assets/b4436be5-e6d7-4d2d-a724-3764122f2abb" width="150"> |
| [Eunsuk](https://github.com/eunsuknoh) | [Younghun](https://github.com/0Huns) | [Hyunggeun](https://github.com/HyungGeun94) |
<br>

## 기술 스택
### 🪄&ensp;프론트엔드 
<div> 
  <img src="https://img.shields.io/badge/react-20232a.svg?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white" />
  <img src="https://img.shields.io/badge/recoil-3578E5?style=for-the-badge&logo=Recoil&logoColor=white">
  <img src="https://img.shields.io/badge/react--query-FF4154?style=for-the-badge&logo=react-query&logoColor=white">
</div>

### 🪄&ensp;백엔드
<div>
  <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white" />
</div>

### 🪄&ensp;배포
<div>
  <img src="https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7" />
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" />
</div>
    
### 🪄&ensp;기타
<div>
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white" />
  <img src="https://img.shields.io/badge/notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white" />
</div>
<br>

## 주요 기능
### 1. 검색 ・ 날씨 카드 

![ws_search](https://github.com/user-attachments/assets/ee4aaf96-70ac-4749-aafb-231ebf790597)

&emsp;3일간의 날씨 카드를 통해 전 세계의 날씨와 옷차림 추천 확인 가능
- [x] OpenWeatherMap API를 사용하여 지역명 or 경도 및 위도에 따른 날씨 ・ 온도 ・ 날짜값 추출
<br> 

### 2. 회원가입 ・ 로그인 

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/user-attachments/assets/62807e40-19d4-4b24-a7ce-e32f8efb2a80" width="400" >
  <img src="https://github.com/user-attachments/assets/725a370d-c095-4771-a0da-78a81d6cb9cc" width="400" >
</div> <br>

&emsp;회원가입 후 로그인을 통해 로그인 유저의 한정된 기능 사용 가능
- [x] 회원가입 - FE ・ BE 이중 유효성 검사 / 리캡챠 기능
- [x] 로그인 - JWT 및 로컬스토리지를 사용하여 로그인, 로그아웃 기능
<br> 

### 3. 마이페이지 

![ws_mypage](https://github.com/user-attachments/assets/9fa0762f-9c21-4547-97b6-40a295a88cd5)

&emsp;로그인 유저 한정) 아바타 이미지 ・ 닉네임 변경 / 비밀번호 변경 / 계정 탈퇴 가능
- [x] JWT 및 로컬스토리지를 사용하여 위 기술된 기능 구현
<br> 

### 4. 방명록 겸 채팅창 

![ws_chat](https://github.com/user-attachments/assets/b2631497-3e6b-452a-a4a2-88d88ee42229)

&emsp;로그인 유저 한정) 방명록 겸 채팅창 사용 가능
- [x] 웹소켓 활용 - 실시간 채팅 기능
<br> 

## 회고 및 소감

`은숙 Eunsuk` 

&emsp;무엇보다도 첫 프로젝트에 좋은 팀원분들을 만날 수 있었음에 너무나 감사하고, 운이 좋았다고 느꼈던 프로젝트였습니다. <br>
&emsp;커뮤니케이션이 어떤 것인지 여실히 알 수 있었고, 스스로의 부족한 점에 대해 깨달을 수 있었으며 <br>
&emsp;정말 다양하고 많은 것들을 배울 수 있었던, 그리고 끝까지 프로젝트를 완수한 자신에게 박수를 쳐주고 싶었던 그런 뜻깊은 경험이었습니다. <br>
&emsp;팀 웨더클로스 정말 고맙습니다 !


`영훈 Younghun` 

&emsp;첫 협업 프로젝트를 진행하면서 혼자 개발할 때는 몰랐던 다양한 문제들과 커뮤니케이션 방법을 해결해가는 경험 속에서 한 단계 성장할 수 있었습니다. <br>
&emsp;또한 혼자가 아닌 팀이기에 클린 코드의 중요성을 느꼈고, 스스로 부족한 부분을 알 수 있었던 계기가 되었습니다. <br>
&emsp;마지막으로 힘들었지만 서로를 믿고 함께 한 좋은 팀원들이 있었기에 여기까지 달려올 수 있었습니다. 고생하셨습니다 !     

`형근 Hyunggeun` 

&emsp;팀 프로젝트의 기본기를 같이 공부하고 구성원들 모두 성장하며 마무리 지을 수 있어서 좋았습니다. <br> 
&emsp;혼자 공부할 때는 인지하지 못했던 부족한 점, 프론트와 백엔드의 협업방식, 커뮤니케이션의 중요성에 대해 알게 되어 의미가 깊었습니다. <br>
&emsp;끝까지 열심히 해준 팀원들에게 고맙다는 말을 하고 싶습니다. 수고하셨습니다 !!


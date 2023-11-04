# StuCamp
<br>

## 👀 소셜, 타이머, 지도, 채팅 기능을 한 번에! <br>공부기록 공유 소셜 어플 '스투캠'
![StuCamp_intro](https://github.com/2023-SMHRD-SW-Fullstack-1/StuCamp/assets/130349912/229f9b1e-f114-4c86-9500-becffb642e5e)

<br>
<br>

## 📅 프로젝트 기간
2023-7-31 ~ 2023-8-4 (1주)
<br>
<br>
## ⭐ 시스템 아키텍처
![image](https://github.com/sin6338ki/StuCamp/assets/130349912/0b80491b-5f08-4320-8cd8-48d2540b12f2)

## ⭐ 주요 기능
* 회원가입 및 로그인
* 카메라 및 갤러리 기능 활용 가능한 피드 작성, 수정, 삭제
* 피드에 대한 댓글 작성/삭제 및 좋아요, 찜하기 기능
* 타이머를 통한 공부 시간 기록 및 캘린더 API 활용 일일 공부시간 출력
* 지도 API 활용 사용자 위치 기반 독서실 위치 공유 
* 오픈 채팅 기능
<br>

## ⛏ 기술스택
![StuCamp_env](https://github.com/2023-SMHRD-SW-Fullstack-1/StuCamp/assets/130349912/707e3486-073c-4bdd-a206-1a409273faa5)
<br>
<br>

## ⚙ 서비스 흐름도
![StuCamp_process](https://github.com/2023-SMHRD-SW-Fullstack-1/StuCamp/assets/130349912/e6fab11f-e0a9-4e5b-86bd-626accb0b76c)
<br>
<br>

## 🖥 시연 영상
https://github.com/2023-SMHRD-SW-Fullstack-1/StuCamp/assets/130349912/77761f92-386d-4d6f-9132-25531ace50e4
<br>
<br>

## 👨‍👩‍👦‍👦 상세 개발 내용
#### 데이터베이스 모델링
- Sequelize를 활용하기 위해 정규화된 엔터티를 설계할 필요성이 있었습니다. ORM을 활용하기 위해 정규화와 관계설정이 잘 이루어진 DB를 설계할 수 있도록 노력했습니다.
#### 데이터베이스 모델링
- 회원 가입과 탈퇴, 댓글(추가, 삭제, 게시글별 댓글 조회), 피드(전체 조회, 마이 피드 조회, 상세 조회, 추가, 삭제, 수정), 좋아요(등록, 삭제, 좋아요 개수 조회)와 관련된 REST API를 설계하고 구현하였습니다. 
- 피드 부분에서 사진 저장을 위해 프론트에서 받은 base64 형식의 이미지를 디코딩하여 UUID로 파일 이름을 생성해 서버에 저장할 수 있도록 구현하였습니다. 
#### Front-End
- Volley를 활용하여 백엔드와 통신해 데이터를 가져오고 이를 화면에 구현하였습니다.
- 댓글 추가, 삭제 기능, 회원별 좋아요 불러오기, 좋아요 추가 및 해제 기능 구현
- 회원별 찜목록 불러오기, 찜하기/찜취소 기능 구현
- 페이지가 로딩되었을 때 사용자가 이전에 좋아요한 게시글이 좋아요 표시가 되도록, 찜한 게시글은 찜완료로 표기되도록 로직을 구현하였습니다.
- Android Studio 디자인 수정(마무리)
![image](https://github.com/sin6338ki/StuCamp/assets/130349912/1570a9a9-7d8f-4649-9c4f-d1703d6e37ac)


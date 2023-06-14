# Movie-And-Chill

Movie-And-Chill은 ChatGPT를 기반으로 한 영화 추천 서비스

사용자에게 맞춤형 영화 추천을 제공하며, 사용자와 자연스럽게 대화하면서 취향에 맞는 영화를 찾을 수 있다.

## 기능

- 사용자와 대화하며 취향에 맞는 영화를 추천
- ChatGPT API를 사용해 자연어 처리와 이해 수행
- 상황 별 영화 추천
- MBTI 유형 별 영화 추천
- 재미있게 본 영화와 유사한 영화 추천

## 사용 기술 및 배포 URL

### 사용 기술

<div>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=flat-square&logo=Tailwind CSS&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
<div>

### 배포 URL

- https://tombeom.github.io/Movie-And-Chill/
  - Github Pages를 통해 배포

## 프로젝트 구조

```
Movie-And-Chill
│  index.html
│
├─img
│  │  bg.png
│  │  chatIcon.png
│  │
│  ├─carousel
│  │      1.png
│  │      2.png
│  │      3.png
│  │      4.png
│  │      5.png
│  │      6.png
│  │      7.png
│  │      8.png
│  │      9.png
│  │
│  └─favicon
│          android-chrome-192x192.png
│          android-chrome-512x512.png
│          apple-touch-icon.png
│          favicon-16x16.png
│          favicon-32x32.png
│          favicon.ico
│          site.webmanifest
│
└─js
        carousel.js
        chat.js
        chatModal.js
        form.js
        init.js
        mbti.js
        menu.js
        messageBox.js
        recommend.js
        similarGenre.js
```

## 상세 기능

- 메뉴 구성
<img src="https://user-images.githubusercontent.com/90359639/245684472-064275b3-9521-4308-876f-810654299c42.gif"/>

```
Main Page, MBTI Page, Similar Genre Page

총 3개의 페이지로 구성되어 있고
리프레시 없이 index.html 내에서 메뉴 변경이 이루어지도록 구성
```

- 사용자와 대화할 수 있는 챗봇
<img src="https://user-images.githubusercontent.com/90359639/245684490-005382cd-4031-45ce-a433-a799d023af28.gif"/>

```
Modal로 구성된 채팅창에서 사용자는 Assistant와 자연스럽게 대화할 수 있다.
```

- 추천 영화 Carousel
<img src="https://user-images.githubusercontent.com/90359639/245684691-5dda4c89-67f1-4b95-9da1-3f8a7a3a43b1.gif"/>

```
추천 영화 리스트를 Carousel로 구현
```

- Modal을 통한 메시지 박스 활성화
<img src="https://user-images.githubusercontent.com/90359639/245684515-f5e7e5b4-ff8c-4081-9d38-b01f9d36df5e.gif"/>

```
채팅창의 메시지를 삭제하거나 사용자가 빈 값을 입력했을 때 Modal로 구성된 Message Box를 활성화한다.
```

- 상황 별 영화 추천
<img src="https://user-images.githubusercontent.com/90359639/245684591-0a10e1b7-97b7-4d32-8423-4dd5b4312851.gif"/>

```
현재 날씨와 분위기 그리고 누구와 함께 영화를 보는지 입력하면 상황에 맞는 영화를 추천
```

- MBTI 유형 별, 유사한 영화 추천
<div>
  <img width="300" src="https://user-images.githubusercontent.com/90359639/245685025-c85c59ef-69c1-4284-902d-5b406e9bf968.png"/>
  <img width="300" src="https://user-images.githubusercontent.com/90359639/245685035-031da89d-b644-44f4-9af8-8ae05429c053.png"/>
</div>

```
MBTI 유형 별 어울리는 영화 추천 및 재미있게 본 영화와 유사한 영화 추천
```

- 반응형 웹 디자인 지원
<div>
  <img width="300" src="https://user-images.githubusercontent.com/90359639/245685008-698b8a20-e99a-44a9-abab-8320a148d3bd.png"/>
  <img width="300" src="https://user-images.githubusercontent.com/90359639/245685016-03b17a56-3485-48db-ba1e-242406bb7a30.png"/>
</div>

```
PC 환경 뿐만 아니라 모바일에서도 웹페이지를 사용할 수 있도록 반응형 디자인을 지원
```

## 개발과정과 시행착오
- SPA


- Carousel


- Responsive Design


# 르세라핌 멤버 소개 사이트
## 1. 제작의도
>  2022년 9월 처음 자바와 스프링을 접한 이후, 개발 지식의 부족함을 느껴 겨울방학 기간을 이용하여 자바, 스프링, 그리고 기본적인 프론트엔드 지식을 함양하고자 하였다. 이에 따라 인프런 무료 강의인 김영한님의 "스프링 입문-코드로 배우는 스프링 부트" 와 유튜버 생활코딩의 "WEB1-HTML", "WEB1-CSS", "WEB2-JavaScript"를 수강한 후 학습한 내용을 점검하고 이에 대한 결과물을 남기고자 걸그룹 르세라핌의 멤버 소개 사이트를 제작하게 되었다. 
## 2. 프론트 기능
> 기초 강의이다보니 특별한 기능은 없지만 부트스트랩이나 jquery와 같은 라이브러리 도움 없이 순수 HTML, CSS, JavaScrpit로만 페이지를 제작하였다.
## 2.1 CSS-Grid
> 그리드 기능을 이용하여 좌측에 내비게이션 바와 본문을 다음과 같이 분리하였다. 
<img width="960" alt="image" src="https://user-images.githubusercontent.com/93889207/221762089-f9fd6811-9a5c-428c-a47d-8933882fde7d.png">

## 2.2 CSS-Media Query
> 미디어 쿼리를 이용하여 반응형 웹으로 스마트폰에서도 동작하도록 하였다.
<img width="377" alt="image" src="https://user-images.githubusercontent.com/93889207/221762814-823abe27-f76b-4856-bf7e-807a4ec87c4a.png">

## 2.3 JavaScript
> 자바스크립트의 기본적인 문법을 활용하여 야간모드 기능을 추가하였다. 활성화 할 경우 음영이 반전되며 <a> 태그들이 'powderblue' 색으로 전환된다.
<img width="960" alt="image" src="https://user-images.githubusercontent.com/93889207/221764307-63e58a4b-79b0-42f2-98ae-ed1399cf8876.png">

## 3. 백엔드 기능
> 방명록 기능을 스프링으로 구현하였다. 기존 강의에서 회원등록 및 조회로 명시되었던 기능을 수정하여 사이트를 다녀간 사람들의 이름 또는 메세지를 남길 수 있도록 간단히 수정하였다.
## 3.1 방명록 등록
> 메세지를 등록하면 데이터베이스에 자동생성 id 값과 함께 메세지가 데이터베이스에 전달된다. 단, 중복된 메세지는 작성할 수 없도록 구현하였다.
<img width="960" alt="image" src="https://user-images.githubusercontent.com/93889207/221766172-b8527e73-982c-4831-b539-560a7fcda26e.png">

<img width="960" alt="image" src="https://user-images.githubusercontent.com/93889207/221766316-dcf34b3b-1101-484d-b4d2-0397c5e0ceb0.png">


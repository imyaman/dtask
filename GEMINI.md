# GEMINI

## Goal

태스크 관리 도구를 만든다.
웹 브라우저에서 동작하는 웹 앱으로 구현한다.

## 기술

Material Design을 사용한다.
npm을 사용한다.
express.js를 사용한다.
vanilla javascript로 구현한다.
웹 라우팅은 navigo를 사용한다. (npm install navigo)
Firebase를 사용한다.
Dooray API를 사용한다.

태스크 정보는 Dooray API로 저장하고 조회한다.
Dooray API로 부족한 것만 Firebase를 이용한다.

## 계정 정보

Firebase 정보는 firebase.js.txt를 참고한다.
Dooray 정보는 dooray.txt를 참고한다.

## 기능

- 태스크를 목록 뷰로 관리할 수 있다.
- 목록 뷰에서 태스크를 다양하게 그룹화하여 볼 수 있다. 그룹화는 2차까지 가능하다.
- 목록 뷰에서 태스크를 다양하게 정렬하여 볼 수 있다. 정렬은 2차까지 가능하다.
- 목록 뷰에서 태스크를 다양하게 필터링하여 볼 수 있다.
- 목록 뷰에서 그룹화/정렬/필터 등을 여러 개 저장하여 빨리 전환할 수 있다.
- 태스크를 보드 뷰로 관리할 수 있다.

## 두레이 참고 사항

- API 문서는 https://helpdesk.dooray.com/share/pages/9wWo-xwiR66BO5LGshgVTg/2939987647631384419 를 참고한다.
- API의 milestone은 UI에 "단계"로 표현한다.
- API의 post는 UI에 "태스크"로 표현한다.

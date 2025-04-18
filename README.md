# 202330234 황충은 react
## 03/13

react는 자바스크립트 UI 내 라이브러리 표방, 2013-5-29공개
페이스북의 개발자 중 하나 Jordan Walke가 개발, 버전 0.3.0으로 소개
18.2.0이전까지만 해도 JS라이브러리임 강조
2023년 리뉴얼 헤드 카피에선 웹과 앱 내 표준 라이브러리로 변신해 가는 모습

## 03/20

## 03/27
react는 component로 생성
component는 고유한 로직과 모양을 가진 UI의 일부
버튼처럼 작을 수도, 전체 페이지처럼 클 수도 있음
마크업을 반환하는 JavaScript 함수

Component의 생성 및 nesting(중첩)
export default 키워드는 파일 내의 component중 기본 component를 지정
이 키워드의 사용도 JavaScript 문법
좀더 구체적으로 알고 싶다면 사이트의 MDN 혹은 javascript.info 링크 확인

export default와 export의 차이

Named Exports
하나의 파일 안 여러 개의 component가 존재할 때 사용
component를 사용하는 쪽에선 정확한 이름 명시 필수

Default Exports
하나의 파일 안에서 하나의 component만 내보내는 경우
사용하는 쪽에서 어떤 이름을 사용하든 상관없음

## 04/03
component 내부 ebent handler 함수 선언하면 event 응답

## 04/10
props를 통해 데이터 전달
com

## 04/17
내가 어느 시점으로 갈 수 있는지 
시간여행 추가
squares 배열 직접 update 시 시간 여행 구현 난이도 매우 높음
하지만 slice() 사용

한 번 더 state 끌어올리기
먼저 export script가 있는
6.다음 플레이어와 플레이 기록을 추적하기 위해 game 컴포넌트에 몇 개의 state 추가
7.현재 플레이에 대한 square를 렌더링하려면 history에서 마지막 squares의 배열 읽어야 한다.
8.렌더링 중에 계산할 수 있는 충분한 정보가 이미 있으므로 useState불필요
현재 state보고싶음 맨 마지막 array
9.다음으로 game component안의 board컴포넌트가 게임을 업데이트할 때 호출할 handlePlay

# 202330234 황충은 react
## 05/22
프로젝트에 react 도입하기
필요한 만큼 react 사용가능(점진적 적용 가능 설계)
새로운 react 시작, 기존에 react 추가, 에디터 설치법, react 개발자 도구 설치법
1. react 사이트에서 샌드박스로 사용가능-단순사용 편의
2. 새로운 앱, 웹 구축하려면 프레임워크부터 시작이 좋음
   2.1. 제약 조건이 있거나, 자체 프레임워크 빌드를 선호하거나, 기본 사항만 배우려는 경우 처음부터 빌드 가능
   2.1.1. 더 많은 유연성을 얻을 수 있지만, 일반적 사용 패턴에 사용할 도구 선택 필요
     자신만의 프레임워크를 구축하는 것과 비슷
   2.2. 풀스택 프레임워크: 프로덕션에서 앱 배포, 확장에 필요한 모든 기능 지원, 서버 필요없음
   2.3. 새로운 react 앱 제작
   2.3.1. Next.js-react의 아키텍처를 최대한 활용하여 풀스택 react 앱을 활성화하는 react 프레임워크
   2.3.1.1. Vercel에서 유지 및 관리 Next.js 앱을 빌드해서 Node.js와 서버리스 호스팅 혹은 자체 서버 배포 가능, 정적 내보내기 가능.
   2.3.1.2. Vercel은 추가로 옵트-인 유료 클라우드 서비스제공
   2.3.2. react router (v7) react에서 가장 인기있는 라우팅 라이브러리, vite와 함께 사용하면 풀스택 react 프레임워크 제작 가능, 표준 Web API, Shopify에서 유지관리
   2.3.3. Expo(네이티브 앱용)
     네이티브 UI 사용 안드로이드, IOS, 웹을 위한 범용 앱 제작 가능 react 프레임워크
     react native SDK 제공
     Expo 사에서 관리
     Expo로 앱 빌드는 무료, 구글이나 애플 스토어에 제한없이 제출 가능
   2.3.4. react 처음부터 시작
   
     
## 05/15
## 05/08
## 04/18
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
## 04/17

## 04/10
props를 통해 데이터 전달
com

## 04/03
component 내부 ebent handler 함수 선언하면 event 응답

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



## 03/20

## 03/13

Node.js는 라이언 달이 개발, 비동기 방식의 서버가 필요하다고 판단하고 개발함
시작 때 파이썬을 사용했으나, 자바스크립트로 방향 전환
당시 크롬이 가장 빠른 브라우저로 주목받고 있었고, 그 핵심인 V8 엔진 사용 결정
Node.js는 웹 서버, 실시간 애플리케이션, 서버리스 환경 등에 활용
빠른 성능, 자바스크립트 풀스택 개발, 활발한 생태계, 실시간 애플리케이션에 강함, 마이크로 서비스 및 서버리스 환경과의 조화로운 연동으로 인기

react는 자바스크립트 UI 내 라이브러리 표방, 2013-5-29공개
페이스북의 개발자 중 하나 Jordan Walke가 개발, 버전 0.3.0으로 소개
18.2.0이전까지만 해도 JS라이브러리임 강조
2023년 리뉴얼 헤드 카피에선 웹과 앱 내 표준 라이브러리로 변신해 가는 모습

npx-create-react-app my-app






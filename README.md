# 리액트 스터디

## Component LifeCycle API
---
1. contructor - 컴포넌트가 생성 될 때
2. componentWillMount - 첫 렌더링 전
3. componentDidMount - 첫 렌+더링 후
4. componentWillReceiveProps - 새로운 Props 를 받았을 때
5. shouldComponentUpdate - 업데이트를 해야할지 말아야할지 정하는 부분
6. componentWillUpdate - 컴포넌트가 업데이트 되기 전
7. componentDidUpdate - 컴포넌트가 업데이트 된 후
8. componentWillUnmount - 컴포넌트가 제거 될 때 실행

### 참고 :
 - https://facebook.github.io/react/docs/react-component.html
 - https://velopert.com/1130

## localStorage
HTML5 부터 지원 되는 2.5mb ~ 5mb 까지 저장이 가능하다.
localStorage는 서버에 전송 되지 않는다.
쿠키처럼 사용할 수 있음.

### 참고 :
– LocalStorage: http://www.w3schools.com/html/html5_webstorage.asp
– 프로젝트 코드: https://github.com/velopert/react-codelab-fundamentals/tree/contact

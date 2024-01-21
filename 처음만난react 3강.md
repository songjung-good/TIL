# 3강 JSX

## JSX의 정의와 역할

### 정의
- jsx = javascript + xml

### 예시
```jsx
const element = <h1>Hello, world!</h1>;
```
- 역할: XML, HTML 코드를 JavaScript로 변환

## JSX의 장점 및 사용법

### 장점
1. 간결해짐
  ```jsx
  <div>Hello, {name}!</div>
  ```
  ```javascript
  React.createElement('div', null, 'Hello, ${name}')
  ```
2. 버그를 발견하기 쉬움
  
3. injection attacks 방어

### 사용법
- 중괄호 {}를 사용하여 javascript코드를 치면 된다.
- 큰 따옴표 사이에 문자

## JSX 코드 작성
1. npx create-react-app 프로젝트명
2. cd 프로젝트명
3. npm start

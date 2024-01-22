# 5강 Components와 Props
- 매우 중요 이해될 때까지 무한 반복

## Components와 Props의 정의
- Component-based
  - 레고 블록 조립하듯 컴포넌트를 조합
  - 컴포넌트는 하나의 틀로써 element를 계속 만들 수 있다.
- Props
  - prop이 여러개 property는 속성
  - prop는 component에 속성(특징)을 부여하는 것
  - 컴포넌트에 전달할 다양한 정보를 담고있는 자바스크립트 객체


## Props의 특징 및 사용법
- Read-only
  - 값을 변경할 수 없다.
  - pure함수 : 입력 값과 출력 값이 일정, 같은 입력 값이면 항상 같은 출력 값
  - impure : 입력(input)값을 변경
    ```javascript
    function withdrawn(account, amount) {
        account.total -= amount;
    }
    ```
  - 모든 리액트 컴포넌트는 props를 직접 바꿀 수 없다(pure해야한다.)


## Component 만들기 및 랜더링



## Component 합성과 추출


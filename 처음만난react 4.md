# 4강 Rendering Elements

## Elements의 정의와 생김새
- elements는 화면에서 보이는 것들을 기술
  - 예시 
    ```javascript
    const element = <h1> Hello World!</h1>;
    ```
- elements의 생김새
  - 리액트의 element는 자바스크립트의 객체형태로 존재
    ```javascript
    ///1 리액트 컴포넌트가 타입인 경우
        type: Button
        props: {
            color: 'green',
            children: 'Hello, element!'
        }
    ///2 타입에 문자열이 들어간 경우
{
        type: 'button'
        props: {
            className: 'bg-green',
            children: {
                type: 'b',
                props: {
                    children: 'Hello, element!'
                }
            }
    }
}
    ```


## elements의 특징 
- react의 element의 불변성(immutable)???
  (- 개발하는데 도움을 준다 그런데 무슨 말인지 잘 이해가 안간다.)
  - elements 생성 후에는 children이나 attributes를 바꿀 수 없다.
    - 화면갱신이 안되는 것인가??
    - elements 생성 후에는 변경이 안되는 것이라 최초에서 변경이 안된다는 뜻
    -> component에서 찍혀나온 element와 비슷하다고 생각하면 된다.> 붕어빵 틀??
  - 빠른 랜더링 -> virtual DOM을 이용
    - 정확히는 모르겠으나 설명을 내 방식대로 정리하자면
    -> virtual DOM에 새로운 element를 적용시키고 Browser DOM을 연결시키면 적용시킨 element는 변하지 않기때문에 DOM에 똑같이 적용된다.

## 실습

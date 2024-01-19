## 의문의 시작

vite를 통해서 프로젝트를 시작하면 두가지의 선택의 순간이 있다.

```bash
√ Select a framework: » 

√ Select a variant: »
```

프레임워크의 선택은 팀 합의를 통해 ‘react’로 결정하였으나

문제는 2번째 선택인 variant이다.

variant는 4가지의 선택지가 있는데

```bash
- TypeScript
- TypeScript + SWC
- JavaScript
> JavaScript + SWC
```

위와 같은 선택지다.

## 의문 1. swc란 무엇인가?

- Rust로 작성된 JavaScript 컴파일러로 Babel의 기능과 유사하지만 빠르고 효율적이다 (Babel의 상위호환)
- JavaScript와 TypeScript의 코드를 트랜스파일하며, ES6+코드를 ES5 이하 버전으로 변환도 가능 (브라우저 호환성 유지)

## 의문 2. swc와 기본선택의 차이

- 기본 선택은 ESbulid를 사용하는 것이다.
- ESbulid는 Go언어로 작성 고성능의 빌드 속도, JavaScript에 최적화, 여러모듈도 지원한다.

## 의문 3. ???

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/67540789-b5cf-4413-b31a-b896e3041adf/f1e26521-52fe-4b3c-b861-efafc6ef9c9e/Untitled.png)

- 그렇다 우리에게 필요한것인가?

## 결론

- 없다.
- 이것저것 해보고 맞는 걸로 선택하겠다 -이상-
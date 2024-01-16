<커밋메시지>

<작성방식>
## git 커밋 메시지 컨벤션
- 다른 사람이 어떤 진행사항인지 알기 쉬움
- conventionalcommits.org 커밋 규칙 제공
- 타입:설명 / 본문 / 꼬리말
  - 타입 : fix와 feat이외의 타입 허용
  - 설명 : 50자 이내로 함축하여 전달
  - 본문 : 가급적 작성 / 왜 수정했는지 설명
- 커밋 메시지를 통해 코드 리뷰어에게 정보제공
  - 커밋단위로 코드리뷰
  - 빠른 리뷰를 위해 리뷰어에게 정보 제공 필요(본문)

## git branch 전략
- git flow 전략
  - master > hotfix > release > develop > feature
  - 브랜치 마다 목적이 명확
  - 브랜치별 생명주기에 따른 처리 주의
- github flow / gitlab flow
  - 단순한 형태로 배포가 매우 잦은 환경에 적합

<유형>
1. new: 새로운 파일, 폴더, 기능 등을 추가한 경우에 사용됩니다. 예를 들어, 새로운 모듈을 추가
2. update: 기존의 기능, 파일, 데이터 등을 업데이트한 경우에 사용됩니다. 예를 들어, 데이터베이스 스키마를 업데이트
3. chore: 일반적인 유지보수 작업이나 코드 정리 등을 수행한 경우에 사용됩니다. 예를 들어, 주석 제거, 코드 리팩토링, 코드 포맷팅 등의 작업을 수행
4. merge: 브랜치를 병합한 경우에 사용됩니다. 예를 들어, feature 브랜치를 develop 브랜치에 병합
5. revert: 이전 커밋을 되돌리는 작업을 수행한 경우에 사용됩니다. 예를 들어, 이전에 잘못된 변경사항을 커밋했을 때 해당 커밋을 되돌리는 작업을 수행
6. refactor: 코드의 구조를 개선하거나 리팩토링한 경우에 사용됩니다. 예를 들어, 중복 코드를 제거하거나 코드 구조 개선이나 변수명, 함수명 변경 등의 작업을 수행
7. feat: 새로운 기능을 추가한 경우에 사용됩니다. 예를 들어, 새로운 기능 개발이 완료
8. fix: 버그를 수정한 경우에 사용됩니다. 예를 들어, 버그 수정이 완료
9. docs: 문서를 수정한 경우에 사용됩니다. 예를 들어, README 파일이나 사용자 매뉴얼 등의 수정사항을 반영한 경우
10. style: 코드 스타일을 수정한 경우에 사용됩니다. 예를 들어, 들여쓰기나 공백 등의 스타일 변경
11. test: 테스트 코드를 추가하거나 수정한 경우에 사용됩니다. 예를 들어, 유닛 테스트나 통합 테스트를 작성하거나 테스트를 통과시키는 작업을 수행
12. optimize: 성능 최적화를 위한 작업을 수행한 경우에 사용됩니다. 예를 들어, 반복문을 개선하거나 캐시를 사용하여 성능을 향상
13. build: 빌드 시스템에 대한 변경사항을 반영한 경우에 사용됩니다. 예를 들어, 빌드 스크립트를 수정했거나 빌드 도구를 변경


<예시>
1. "Feat feature to login functionality"
    로그인 기능에 새로운 기능을 추가한 경우
2. "Fix bug in registration form validation"
    회원가입 양식 유효성 검사에서 버그를 수정한 경우
3. "Update README with project setup instructions"
    프로젝트 설정 방법을 설명하는 README를 업데이트한 경우
4. "Refactor database query for better performance"
    성능 향상을 위해 데이터베이스 쿼리를 리팩토링한 경우
5. "Merge feature/add-user-profile branch into develop"
    feature/add-user-profile 브랜치를 develop 브랜치로 병합한 경우
6. "Revert previous commit that caused unexpected behavior"
    이전 커밋으로 인해 예기치 않은 동작이 발생한 것을 되돌린 경우
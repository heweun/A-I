# A-I : 깃허브 규칙
## READ ME

- README 는 간단하게라도 작성한다.
- 리드미의 용도는 이 프로젝트가 무엇인지 그리고 어떻게 동작하는지에 대해 설명하는 기본 자료
- 리드미가 없으면 프로젝트를 다른 사람이 이해하는데 쉽지 않을 수 있다.
- README Template Guide
    - https://github.com/othneildrew/Best-README-Template
- 처음부터 Best Case 로 작성하지 않아도 된다.
- 작성을 하고 계속 갱신하는게 중요하다.

## 브런치 전략

- Git Flow 를 기반으로 Github 을 활용한 Github Flow 를 선호
- Git Flow → https://danielkummer.github.io/git-flow-cheatsheet/index.ko_KR.html

## Code Convention

- 변수와 메소드 명은 명확하게 작성
- 주석은 가급적 지양, Document 를 위한 주석은 Document 수준으로 작성 (그렇지 않다면 제외)
- 각 언어 별로 표준 가이드를 지향
    - 파이썬 : [http://pythonstudy.xyz/python/article/511-파이썬-코딩-스타일](http://pythonstudy.xyz/python/article/511-%ED%8C%8C%EC%9D%B4%EC%8D%AC-%EC%BD%94%EB%94%A9-%EC%8A%A4%ED%83%80%EC%9D%BC)
    - 자바 : https://github.com/JunHoPark93/google-java-styleguide?tab=readme-ov-file
    - 자바스크립트: https://standardjs.com/rules-kokr
- 하나의 Repository 의 각 코드를 작성 할 때 하나의 프로그래밍 표기법만 준수 (혼용 금지)
    - 스네이크, 카멜, 파스칼 중에 선택
- 메소드, 함수 명은 동사로 시작 ( ex) createMember(), deleteContent)
- 이해하기 어려운 약어는 가급적 지양

## Commit Message

- 커밋 메시지는 간결하고 짧게 구성한다.
- 많은 파일은 커밋하기 보다 적은 파일의 수로 커밋한다.
- 하나의 커밋에 하나의 목적만 있는게 좋다.

## Code Review

- 코드 리뷰가 되지 않은 코드는 머지 되지 않는다.
- 코드 리뷰는 프로젝트의 필수 요소.
- 코드 리뷰 기본 정책
    - https://tech.kakao.com/2022/03/17/2022-newkrew-onboarding-codereview/
- 코드 리뷰의 목적
    - 코드 리뷰는 팀의 발전이 목표
    - 좋은 퀄리티의 Product 를 만들어내는데 목표가 있다.
    - 가독성이 좋은 코드. 유지보수하기 좋은 코드가 목표
    - 팀 모두가 프로젝트에 대한 이해도가 높아지는 것이 목표
    - 목적없는 비난과 비판은 지양
    - **서로 함께 성장할 수 있는 피드백을 지향**
- 코드리뷰는 Github PR 을 활용한 온라인 리뷰, 함께 모여서 진행하는 오프라인 리뷰로 나눈다.
    - 온라인 리뷰
        - Commit Message 와 Code Diff 를 중심으로 리뷰 한다.
        - 리뷰어가 파악할 수 있는 범위 내에서만 점검한다.
    - 오프라인 리뷰
        - 개발을 한 의도와 방향성에 대해 컨센서스를 맞추는 것이 목표
        - 온라인에서는 서로 주고 받기 어려운 구조적인 부분에 대해 서로 논의하는 자리
        - 온라인 리뷰와 별개로 오프라인 리뷰도 필수로 진행 (머지를 한 코드라도 오프라인 리뷰는 진행)

### 10장 도메인

- 도메인은 애플리케이션이 해결하고자 하는 문제 영역을 의미.
- 사업가 입장에서 소프트웨어 시스템을 만들게 되는 계기.
  - 사용자가 겪는 문제를 해결해주는 것이 비즈니스.
  - 소프트웨어는 그러한 해결책 중 하나로 선택.
- 린
  - 군더더기 없는이라는 뜻으로 도요타의 생산(learn production) 사례를 통해 크게 유명해짐.
  - 린 스타트업.
  - 린 방식의 업무 스타일.
- 사용자들이 겪는 문제 영역이 바로 도메인.
- 우리가 개발해야할 것은 애플리케이션이 아니라 `도메일 어플리케이션`임.
- 도메인을 분석하고 사용자들이 겪는 문제를 인지해 소프트웨어적인 해결책을 제시할 수 있어야 함.
- 도메인 모델과 영속성 객체(JPA Entity)는 구분해야 하는가?
  - 통합할 경우.
    - 개발속도가 빠름.
    - 단일 책임 원칙을 위반함.
    - 데이터베이스 스키마 변경이나 마이그레이션 걱정을 먼저하게 됨. 👉 데이터베이스 위주의 사고가 됨.
  - 분리할 경우.
    - 개발 속도가 느려짐.
    - 작성해야 하는 코드 양이 늘어남.
    - 데이터베이스 변경에 따른 도메인의 변경이 일어나지 않아도 됨.

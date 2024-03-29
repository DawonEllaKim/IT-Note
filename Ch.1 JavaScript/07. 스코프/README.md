# 7. 스코프

## 📍 스코프란 (scope)?

- 모든 식별자(변수 이름, 함수 이름, 클래스 이름 등)는 자신이 선언된 위치에 의해 다른 코드가 식별자 자신을 참조할 수 있는 유효 범위가 결정된다. 이를 스코프라 한다. 즉, 스크포는 식별자가 유효한 범위를 말한다.

## 📍 스코프의 종류

- 전역이란?
  - 전역이란 코드의 가장 바깥 영역을 말한다.
  - 전역은 전역 스코프를 만든다. 전역에 변수를 선언하면 전역 스코프를 갖는 전역 변수가 된다.
  - 전역 변수는 어디서든지 참조할 수 있다.
- 지역이란?
  - 지역이란 함수 몸체 내부를 말한다.
  - 지역은 지역 스코프를 만든다. 지역에 변수를 선언하면 지역 스코프를 갖는 지역 변수가 된다.
  - 지역 변수는 자신의 지역 스코프와 하위 지역 스코프에서 유효하다.

## 📍 스코프 체인이란?

- 함수는 다른 함수의 몸체 내부에서 정의가 될 수 있다. 이것을 함수의 중첩이라고 한다.
- 함수의 중첩이 일어날때, 스코프 또한 중첩이 되는데 이를 스코프가 함수의 중첩에 의해 계층적 구조를 갖는다고 표현한다.

---

## 내가 타입스크립트의 배울려는 목표

- 문법을 공부하지만 다른 타입스크립트 라이브러리 분석을 목표

<br>

### 내가 왜 타입스크립트를 배울려고 할까? 궁리해보자

- 일단 정보를 찾는데 있어서 타입스크립트 또한 사람들이 자주 쓰다보니까 원하는 정보를 찾았지만 타입스크립트로 되어있어 내가 이해할수 없고 **답답함을 느꼈음** (이게 가장 크다!!) → React Native 프로젝트에 적용할 때 라이브러리 필요했고 이를 응용해서 딥러닝과 적용해야 할때 타입 스크립트로 되어있어서 애를 먹었던 기억이 새록새록 난다.
- 내 수준에서는 자바스크립트의 에러를 못고쳐서 타입스크립트를 사용하는 이유는 아니나, 내가 발견 못하는 타입에 문제로 JS에서는 넘어가는 문제를 확실하게 타입스크립트에서 경험해 보고 싶다.
- 회사에서 스프링 작업 (즉 자바)를 하면서 느낀게 타입을 객체마다 다 지정하고 반환할 때마저 타입을 기입한다.
  - 그 이유가 무엇일까? 사소한 에러마저 잡겠다는 철학이 담겨 있었고, 내가 사용하는 JS에서도 이렇게 타입을 지정해준다면 안정성이 올라갈 것이라고 느꼈다.

<br>

장점만 있을까?? 단점은 무엇일까??

- JS보다는 다이나믹, 즉 자유도가 떨어진다
- 하지만 회사에서는 에러, 문제가 없는 안정성이 더 중요하다고 생각한다

<br>

### 타입스크립트 철학 목표는?

JavaScript 프로그램의 정적 타입 검사자이다. 즉, 코드가 실행되기 전에 실행하고(정적), 프로그램 타입이 정확한지 확인하는 도구(타입 검사)이다.

정적 타입 검사자 의미?

- 프로그램을 실행시키지 않으면서 코드를 오류를 검출 하는 것

JS 런타임 특성을 바꿨을까?

- 타입스크립트는 JS 런타임 특성을 가진 프로그래밍 언어이다. 절대 변화시키지 않는다. 그러기에 코드 타입에 오류가 검출되도 실행시킨다. → JS, TS 쉽게 전환되는게 TS언어의 철학이다

<br>

### TypeScript 철학, 의미

언어가 다른 것이 아니다 → **TypeScript는 컴파일-타임 타입 검사자가 있는 JavaScript의 런타임**

- TypeScript에서 타입은 공통의 무언가를 공유하는 **값의 집합**으로 생각하는 것이 좋다.
- TypeScript에서 모든 타입이 단순히 집합이라는 것을 깨닫는 순간 이는 매우 자연스러워진다
- TypeScript는 OOP 객체지향언어처럼 사용가능하다. 또한 자유롭게 함수로 사용해도 되고 데이터를 자유롭게 처리할 수 도 있다.

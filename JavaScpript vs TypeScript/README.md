# 📘 TypeScript vs JavaScript

## 🤔 왜 TypeScript가 등장했을까?

JavaScript는 변수에 타입을 명시하지 않아 해당 변수가 어떤 타입인지 파악하기 어려운 문제가 있습니다.  
특히 협업 시 다른 사람의 코드를 읽을 때 변수의 의도를 파악하기 힘들고, 런타임에서야 타입 오류를 발견할 수 있다는 단점이 있습니다.

이를 보완하기 위해 **TypeScript**가 등장했습니다.

---

## ✅ TypeScript의 장점

- **타입 명시** — 변수에 타입을 직접 선언해 코드의 의도를 명확하게 전달할 수 있습니다.
- **협업 효율 향상** — 다른 개발자가 코드를 파악하기 쉬워 협업 시 생산성이 높아집니다.
- **오류 사전 방지** — 컴파일 단계에서 타입 오류를 미리 잡아낼 수 있습니다.
- **데이터를 잘 표현** — 타입을 통해 데이터 구조를 명확하게 표현할 수 있습니다.

---

## 💡 코드 예시

```typescript
type Centimeter = number;
type RainbowColor = 'red' | 'orange' | 'yellow' | 'green' | 'blue' | 'indigo' | 'violet';

let age = 10;
let weight: number = 80;
let height: Centimeter = 180;
let color: RainbowColor = 'orange';

color = 'black'; // ❌ Error: Type '"black"' is not assignable to type 'RainbowColor'.
```

> `RainbowColor` 타입처럼 허용할 값을 직접 정의하면, 잘못된 값이 들어왔을 때 컴파일 단계에서 바로 오류를 감지할 수 있습니다.

---

## 🔄 JavaScript를 대체하는 언어가 아니다

TypeScript는 JavaScript를 **대체**하는 언어가 아닙니다.  
**트랜스파일러**를 통해 최종적으로 JavaScript로 변환되어 실행되기 때문에, 기존 JavaScript 생태계를 그대로 활용할 수 있습니다.  
이 점 덕분에 많은 개발자들에게 사랑받고 있습니다.

---

## 📌 정리

| 구분 | JavaScript | TypeScript |
|---|---|---|
| 타입 선언 | ❌ 없음 | ✅ 명시 가능 |
| 오류 감지 | 런타임 | 컴파일 단계 |
| 협업 편의성 | 낮음 | 높음 |
| 실행 방식 | 직접 실행 | 트랜스파일 후 실행 |

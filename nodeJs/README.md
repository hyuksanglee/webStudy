# 📘 Node.js & npm

## 🤔 Node.js는 왜 탄생했을까?

기존 JavaScript는 브라우저에서만 실행할 수 있는 언어였습니다.  
**"JS 파일을 브라우저 밖에서도 실행할 수 없을까?"** 라는 아이디어에서 출발해  
2009년 **라이언 달(Ryan Dahl)** 에 의해 Node.js가 탄생했습니다.

Node.js는 Chrome의 **V8 엔진**을 기반으로 만들어졌으며, 이를 통해 JavaScript를 서버, 로컬 환경 등 다양한 곳에서 실행할 수 있게 되었습니다.

---

## ✅ Node.js의 특징

- **브라우저 밖에서 JS 실행** — 서버, CLI 도구 등 다양한 환경에서 JavaScript를 사용할 수 있습니다.
- **비동기 I/O** — 논블로킹 방식으로 동작해 빠른 처리가 가능합니다.
- **거대한 생태계** — npm을 통해 수많은 라이브러리를 활용할 수 있습니다.

---

## 📦 npm이란?

**npm(Node Package Manager)** 은 Node.js와 함께 등장한 패키지 관리 도구입니다.  
전 세계 개발자들이 만든 라이브러리를 등록하고 쉽게 설치·업데이트·관리할 수 있습니다.

- 라이브러리 검색 및 설치가 간편
- 버전 관리 및 업데이트 용이
- `package.json`으로 프로젝트 의존성을 일괄 관리

---

## 💡 코드 예시

```javascript
var colors = require('colors');

console.log("Hello World!".rainbow);
```

> `colors` 라이브러리를 npm으로 설치한 후 `require`로 불러와 사용합니다.  
> 이처럼 npm을 통해 복잡한 기능도 간단하게 추가할 수 있습니다.

---

## 📌 정리

| 구분 | 설명 |
|---|---|
| Node.js | 브라우저 밖에서 JavaScript를 실행할 수 있는 런타임 환경 |
| npm | Node.js 기반의 패키지 관리 도구 |
| V8 엔진 | Node.js의 기반이 되는 Chrome의 JavaScript 실행 엔진 |
| package.json | 프로젝트의 라이브러리 의존성을 관리하는 설정 파일 |

![enter image description here](https://user-images.githubusercontent.com/24728385/148955263-b3a0e063-6950-46f2-82e9-1fcabc24e19e.jpeg)

<h1 align="middle">[과제] 에이팀벤처스</h1>

1. Typescript로 구현
2. Figma 가이드를 따르기

# 🔗 배포

[에너지밸런스 과제 배포 링크](https://angry-albattani-8e8937.netlify.app/)
[![Netlify Status](https://api.netlify.com/api/v1/badges/a580b2b0-c471-4339-9128-f18b39de1a34/deploy-status)](https://app.netlify.com/sites/angry-albattani-8e8937/deploys)

# ⚙️ 설치 및 시작하는 법

```
$ git clone https://github.com/pre-onboarding-course-team-6/2nd-week-ateam-ventures

$ cd 2nd-week-ateam-ventures

$ npm install

$ npm run start
```

# 🏹 구현 목록

## 필터링 기능구현 ( 가공방식 & 재료 )

gif

필터링 조건이 가공방식, 재료, 상담중 여부 3가지가 있다.
재료가 구리, 알류미늄이 선택되었다면 구리 or 알류미늄이고 가공방식에서 밀링, 재료는 구리가 선택되었다면 밀링 and 구리 이다.
여기에 중복선택이 가능하고 필터링 조건이 3가지라 복잡한 구조가 되었다.

이때 프로그래밍 패턴 이라는 책에서 읽은 파이프라인 구조가 떠올랐다.
![image](https://user-images.githubusercontent.com/40172373/156318361-f44be7e5-3a42-4e3a-9513-f5d7e86aa4f9.png)

데이터를 가공방식, 재료, 상담중 여부를 3번에 걸쳐 필터링을 했다.

# 🏗 폴더 구조
작성한 코드😀

```
📦src
 ├──📂commons
 │   ├── 📜common.ts
 │   ├── 📜type.ts
 │   └── 📜utils.ts 😀
 ├──📂components
 │   ├──📂Card
 │   │   └──📜index.tsx
 │   ├──📂Container
 │   │   └──📜index.tsx 😀
 │   └──📂Header
 │       └──📜index.tsx
 ├──📂style
 │   ├──📜global.ts
 │   ├──📜style.ts
 │   ├──📜styled.d.ts
 │   └──📜theme.ts
 ├──📜App.css
 ├──📜App.tsx
 ├──📜index.css
 └──📜index.tsx
```

## ✅ Git - Commit Message Convention [🔗](https://webruden.tistory.com/486)

- feat : 새로운 기능 추가 (a new feature)
- fix : 버그 수정 (a bug fix)
- docs : 문서 수정 (changes to documentation)
- style : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우 (formatting, missing semi colons, etc; no code change)
- refactor : 코드 리펙토링 (refactoring production code)
- test : 테스트 코드, 리펙토링 테스트 코드 추가 (adding tests, refactoring test; no production code change)
- chore : 빌드 업무 수정, 패키지 매니저 수정 (updating build tasks, package manager configs, etc; no production code change)

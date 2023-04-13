## **[Vite js](https://vitejs.dev/)**

![img](https://vitejs.dev/og-image-announcing-vite3.png)

## Vite js란?

- 빠르고 간결한 웹 프로젝트 개발에 초점을 맞춘 빌드 도구
- ES Module을 기반으로 한 Dev Server
- 기존의 ESM에서는 모듈화 문법 `import, export`을 사용하여 번들링

  - webpack이란?

    - 웹을 구성하는 모든 자원을 `모듈`이라고 한다 (html, js, img...)

    - 웹을 구성하는 수많은 모듈들을 하나의 파일로 병합/압축하는 것을 `모듈 번들링`이라고 한다.

  > 즉, 모듈을 번들링 해주는 모듈 번들러를 웹팩이라고 한다.

- Vite는 번들링하지 않고 ESM방식을 사용하여 속도가 매우 빠르다

  - 웹팩은 로컬서버를 시작할때 관련 모듈들을 번들링하여 메모리에 적재할 시간이 필요하다.

  - 이에 반해 Vite는 번들링을 하지 않고 서버를 시작하기 때문에 명령어 실행과 동시에 서버 실행이 가능하다.

## Vite 시작하기

### 프로젝트 생성

```bash
   # npm
   npm create vite@latest vite_prac

   # react 템플릿 생성
   npm create vite@latest vite_prac -- --template react

   # TypeScript react-ts 템플릿 생성
   npm create vite@latest vite_prac -- --template react-ts

   # yarn
   yarn create vite
```

### 실행

```bash
    npm run dev
```

![img](https://velog.velcdn.com/images/homile/post/f4b6319a-f682-419b-8764-04925b4d2e2f/image.gif)

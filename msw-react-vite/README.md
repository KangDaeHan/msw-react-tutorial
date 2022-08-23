# msw-react-vite

[Mock Service Worker](https://github.com/mswjs/msw) 를 사용한 REST API Mocking 튜토리얼 (보일러 플레이트)

## 기술 스택
![image](https://user-images.githubusercontent.com/71962505/186138244-75b1a113-41e8-4db4-a85d-01fbd2377223.png)
<br>
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/Vite-14CC80?style=for-the-badge&logo=vite&logoColor=black">
<img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=black">


## 설치
```
$ git clone https://github.com/somedaycode/msw-react-tutorial.git
$ cd msw-react-vite
$ yarn
```

## 시작

```
$ yarn dev
```

## 참고 파일

---
- `src/mocks/handlers.ts` HTTP Request 요청을 다룬다. 

### Browser
- `public/mockServiceWorker.js` : 서비스워커(Service Worker), `npx msw init public` 명령어로 생성되는 파일
- `src/mocks/browser.ts` : 서비스워커를 설치한다.
- `src/main.tsx` : 개발 서버 실행시 API Mocking이 가능하도록 한다.

---

## 아티클

[MSW(Mock Service Worker)를 사용한 네트워크 단 API Mocking 테스트](https://somedaycode.tistory.com/27)

electron 설치및 빌드

중요한 파일 index.js(electron 설정)
해당 파일에서 실행할 index.html 파일을 연결한다.
 - win.loadURL(`file://${__dirname}/index.html`);


일렉트론 설치
- npm install --save-dev electron

일렉트론 빌드
- npm install --save-dev electron-builder

일렉트론 win64 스크립트 실행
- npm run build:win64

세부 설정은 package.json에 bulid 설정([옵션참고](https://www.electron.build/configuration/configuration,"옵션참고"))과 script 부분의 run build 참고
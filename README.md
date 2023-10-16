# p5-template-esm

ES6 모듈과 Vite.js 번들러를 사용한 p5js 템플릿 코드.

A barebone `p5.js` template using ES6 module and Vite.js bundler.

## 준비물

- [Node.js](https://nodejs.org/en) 설치가 필요하다.

## 사용방법

1. 터미널 앱에서 템플릿을 저장할 경로로 `cd` 커멘드를 사용해서 이동해준다.
2. `git clone https://github.com/dizicoder/p5-template-esm.git` 또는 `gh repo clone dizicoder/p5-template-esm` 명령어를 실행한다.
3. `cd p5-template-esm` 명령어를 실행해서 폴더 안으로 이동한다.
4. `npm install` 명령어를 실행해서 필요한 패키지들을 설치한다.
5. `npm run dev` 명령어를 실행하면 로컬서버와 스케치가 실행된다.
6. 터미널에 표시된 URL을 브라우저에서 열어준다. 예: `http://localhost:5173`.
7. `src/index.js` 파일을 사용해서 스케치 코드를 작성한다.
8. 이미지 등의 외부파일은 `public` 폴더에 넣어준다.
9. `npm install <name>` 명령어를 사용하면 추가로 필요한 패키지들을 설치할 수 있다.
10. 완성한 스케치는 `npm run build` 명령어를 사용해서 웹에 올릴 파일을 만들어줄 수 있다.

---

## Prerequisites

- [Node.js](https://nodejs.org/en) needs to be installed on your machine.

## How to use

1. in Terminal, `cd` into where you want to save the template.
2. Run `git clone https://github.com/dizicoder/p5-template-esm.git` or `gh repo clone dizicoder/p5-template-esm`.
3. Run `cd p5-template-esm`.
4. Run `npm install` to install the dependencies.
5. Run `npm run dev` to run the local server and the sketch.
6. Go to the URL displayed in the Terminal. ie. `http://localhost:5173`.
7. Write your sketch code in `src/index.ts`.
8. Use `public` folder to store any external files such as images.
9. If you need to install additional NPM packages, Run `npm install <name>`.
10. When you are ready to upload your sketch on the web, run `npm run build` to generate build files.

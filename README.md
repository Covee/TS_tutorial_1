# TS_tutorial_1
making blockchain with TS | tutorial

## should know this!
1. ```yarn init``` 으로 프로젝트 생성 후, tsconfig.json 만들어준다.
2. tsconfig.json 설정
3. index.ts 만들어 준다.(** 터미널에 tsc 명령 내리면 index.ts에 있는 ts코드를 컴파일해서 index.js 와 index.js.map을 생성해준다.)
4. package.json에 등록한 script 명령어 중, prestart는 start 명령을 내리면 자동으로 먼저 실행되고 난 후 start가 실행된다.(실행순서: prestart -> start)
5. node.js는 TS를 이해하지 못하기 때문에 일반적인 JS 코드로 컴파일 하는 작업이 꼭 필요함.
6. 
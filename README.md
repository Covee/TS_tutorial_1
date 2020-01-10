# TS_tutorial_1
making blockchain with TS | tutorial

## should know this!
1. ```yarn init``` 으로 프로젝트 생성 후, tsconfig.json 만들어준다.
2. tsconfig.json 설정
3. index.ts 만들어 준다.(** 터미널에 tsc 명령 내리면 index.ts에 있는 ts코드를 컴파일해서 index.js 와 index.js.map을 생성해준다.)
4. package.json에 등록한 script 명령어 중, prestart는 start 명령을 내리면 자동으로 먼저 실행되고 난 후 start가 실행된다.(실행순서: prestart -> start)
5. node.js는 TS를 이해하지 못하기 때문에 일반적인 JS 코드로 컴파일 하는 작업이 꼭 필요함.
6. parameter뒤에 ? 붙으면 optional로 만들어주는 것.
7. dev 환경에서 tsc-watch 쓸 수 있게 설치 ```yarn add tsc-watch --dev```
8. src 디렉토리 생성해서 기존 index.ts를 src 안으로 옮겨주고 dist 디렉토리 생성(dist는 tsc 한번 돌려서 src/index.ts로부터 생성되는 자바스크립트 코드들)
9. tsconfig.json과 package.json 경로와 설정 등 변경(변경사항 check out)
10. interface는 객체를 타입화해서 받을 수 있는 장치.
11. interface가 class보다 더 TS스럽지만(?) react, node 등을 쓸땐 class를 대개는 쓸 수 밖에 없다.
12. class는 반드시 하나의 constructor를 가지게 되고 이것은 class가 쓰여질 때 마다 호출된다.
13. public은 외부에서도 자유롭게 접근 가능, private은 외부에서 접근 불가능.
14. 만들어진 class를 이용해 객체를 생성해 줄 때, ```new (class명)``` 이런 식으로.
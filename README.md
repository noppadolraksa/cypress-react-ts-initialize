1. npm i cypress @cypress/instrument-cra @cypress/code-coverage start-server-and-test
2. tsconfig.json => add {"types":["cypress"]}
3. add gitignore
4. create cypress folder , delete jest setting in package.json

**run test :**<br/>
//run test with no starting server
npm run cypress:start:app

//start server and run cypress:start:app then wait http://localhost:3000<br/>
npm run cypress:start:wait

//run for development<br/>
npm run cypress:open

//run for ci server in headless mode<br/>
npm run cypress:run

**coverage log :**<br/>
open coverage/lcov-report/index.html

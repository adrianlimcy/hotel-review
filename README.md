# Setting Up
1.  Download the file from https://github.com/PacktPublishing/React-Projects/tree/ch6-initial
2.  npm install
3.  npm audit fix
4.  npm start
5.  Unit testing using Jest
        - npm run test
6.  touch src/components/Header/SubHeader.test.js
7.  npm install react-test-renderer --save-dev
8.  create the test scenarios in the SubHeader.test.js file
9.  npm run test --coverage
10. touch src/components/Button/Button.test.js

# Using Enzyme
- Good to test for events like onClick
1.  npm install enzyme enzyme-adapter-react-16 --save-dev
2.  touch src/setupTests.js

# Integration
1.  touch src/components/Hotels/Hotels.test.js
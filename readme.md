Project Description: API test for https://reqres.in/ as follow

1. should return correct users list elements
2. should return correct user
3. should login successfully
4. should login unsuccessfully without email
5. should login unsuccessfully without passowrd

Installation:
1. ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
2. brew install node
3. npm install

Test execution:
1. npm test: run all test
2. npm run smoke: run all test result marked as smoke
3. npm run regression: run all test result marked as regression
4. npm run getUser: run get user test cases
5. npm run loginTest: run login test cases
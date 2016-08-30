# React native tests example

Simple example to get your started with React-Native and Redux and how to test the hell of it.

with this repository you'll learn stuff like : 
    
  - How to run tests using [Mocha.js][Mocha]
  - How to write tests using assertion librery like [Chai.js][Chai]
  - How to use code coverage tool like [nyc][nyc]
  - How to run some component snapshot tests using Facebook's [Jest][Jest]
  - How to run some component tests using [Enzyme][Enzyme]
  - How to write end to end tests using [webdriver.io][Webdriver] and run it using [Appium][Appium]
  
# Run Instructions
first
```sh
npm install
```
  
 then 
 
 ### Running unit tests + Enzyme with some coverage test
 
 ```sh
npm test
```

### Running Jest snapshot tests
```sh
npm run testjest
```

### Running Jest snapshot tests in update mode
```sh
npm run testsjest_update
```

### Running End to End tests
```sh
npm start
npm run appium
npm run run-e2e
```


[Chai]: <http://chaijs.com/>
[Mocha]: <https://mochajs.org/>
[Jest]: <https://facebook.github.io/jest/>
[Appium]: <http://appium.io/>
[Webdriver]: <http://webdriver.io/>
[Enzyme]: <http://airbnb.io/enzyme/>
[nyc]: <https://github.com/istanbuljs/nyc>




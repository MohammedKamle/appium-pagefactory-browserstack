# appium-pagefactory-browserstack
This repository demonstrate how we can integrate both iOS and android test with the same script using PageFactory on BrowserStack. 
## Libraries used
```
Appium
JUnit 4
Cucumber-JUnit
jackson-databind
json-simple
```
## Build Management Tool
Maven


## How to run the test ?
  - Clone the project 
  - Build the project using:
```
mvn clean install
```
  - Give your BrowserStack specific username and accessKey along with your app identifier in [`config.yml`](https://github.com/MohammedKamle/appium-pagefactory-browserstack/blob/master/src/test/resources/config.yml) 
  - Run the cucumber test runner class [TestRunner](https://github.com/MohammedKamle/appium-pagefactory-browserstack/blob/master/src/test/java/com/browserstack/tests/TestRunner.java)
### Tes Results 
You can view the executed tests on your [`app-automate`](https://app-automate.browserstack.com/dashboard) dashboard on BrowserStack 

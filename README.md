# Automation Testing with Selenium and JavaScript
<a href="https://selenium.dev"><img src="https://selenium.dev/images/selenium_logo_square_green.png" width="180" alt="Selenium"/></a>

Selenium is an umbrella project for a range of tools and libraries that enable and support the automation of web browsers.

Allows users to simulate common activities performed by end-users; entering text into fields, selecting drop-down values and checking boxes, and clicking links in documents.
Browser user agent library.
Execute on Firefox, Internet Explorer, Chrome, and all other supported browsers.

## Documentation

Narrative documentation:

* [User Manual](https://selenium.dev/documentation/)

#### JavaScript
<details>
<summary>Click to see JavaScript Build Steps</summary>

If you want to build all the JavaScript code you can run:

```sh
bazel build javascript/...
```

To build the NodeJS bindings you will need to run:

```sh
bazel build //javascript/node/selenium-webdriver
```

To run the tests run:

```sh
bazel test //javascript/node/selenium-webdriver:tests
```

You can pass in the environment variable `SELENIUM_BROWSER` with the name of the browser.

To publish to NPM run:

```sh
bazel run //javascript/node/selenium-webdriver:selenium-webdriver.publish
```
</details>

## Getting Started

You need to install either [Yarn](https://yarnpkg.com/en/) or [Node](https://nodejs.org/en/) on your machine. In this project, I will use npm for installing packages and running scripts.

```sh
npm install
```

## Running UI Test

```sh
npm run test
```

## References

Getting started :: Documentation for Selenium

SeleniumHQ/seleniumhq.github.io: Official Selenium website and documentation

Selenium Cheat Sheet - DEV Community

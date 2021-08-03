# Selenium Installation

JavaScript
Installation of Selenium libraries for JavaScript can be done using npm:

``
npm install selenium-webdriver
``

``
To execute your project and control the browser you need to have browser-specific WebDriver binaries installed.

Download the WebDriver binary supported by your browser and place it in the System PATH.
``

``
If you plan to use Grid then you should download the selenium-server-standalone JAR file. All the components are available via selenium-server. The standalone JAR contains everything, including the remote Selenium server and the client-side bindings. This means that if you use the selenium-server-standalone jar in your project, you do not have to add selenium-java or a browser specific jar.

<dependency>
 <groupId>org.seleniumhq.selenium</groupId>
 <artifactId>selenium-server</artifactId>
 <version>3.X</version>
</dependency>

``

## Install Dependencies

Selenium WebDriver

If you want to create robust, browser-based regression automation suites and tests, scale and distribute scripts across many environments, then you want to use Selenium WebDriver, a collection of language specific bindings to drive a browser - the way it is meant to be driven.

Selenium IDE

If you want to create quick bug reproduction scripts, create scripts to aid in automation-aided exploratory testing, then you want to use Selenium IDE; a Chrome and Firefox add-on that will do simple record-and-playback of interactions with the browser.

Selenium Grid

If you want to scale by distributing and running tests on several machines and manage multiple environments from a central point, making it easy to run the tests against a vast combination of browsers/OS, then you want to use Selenium Grid.

##References
https://github.com/SeleniumHQ/selenium
selenium.dev
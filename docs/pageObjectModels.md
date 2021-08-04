# Page Object Model

A page object is an object-oriented class that fills in as a interface to a page of your UAT.

The tests then use the methods of this page object class at whatever point they have to connect with the UI of the page

## Using Page Objects

This is an useful technique in Selenium tests that allows functionality to be separated into different classes based on pages or area of functionality in the application. The benefits to this are that it can be easy to organize test code and helps to keep the test class, itself, even more clean and readable.


## Design Pattern

Enhance test maintenance and reduce code duplication

## Object Oriented Class

Interface to a page of the application under test (UAT)

## Page Object Design Pattern Advantages

There is a clean separation between test code and page specific code such as locators (or their use if you’re using a UI Map) and layout.

There is a single repository for the services or operations offered by the page rather than having these services scattered throughout the tests.


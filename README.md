## Table of Contents

* [Project Overview](#Project-Overview)
* [Dependencies](#Dependencies)
* [Instructions](#Instructions)
* [Completed Set of Tests](#Completed-Set-of-Tests)

## Project Overview

In this project you are given a web-based application that reads RSS feeds. A complete set of test suite has been added to the project to make sure the application is running properly. 

## Dependencies

* [Jasmine](http://jasmine.github.io/)

## Instructions

* After cloning or downloading the whole project folder, open `index.html` in the root folder. You will find the RSS Feed application running on the page as well as the Jasmine testing results displayed at the bottom of the page.
* All the current set of tests should pass(failure number should be 0).
* All the test code is located in the `./jasmine/spec/feedreader.js`.

## Completed Set of Tests

1. A test that makes sure that `allFeeds` variable has been defined and that it is not empty.
2. A test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
3. A test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
4. A test that ensures the menu element is hidden by default. 
5. A test that ensures the menu changes visibility when the menu icon is clicked. 
6. A test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
7. A test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.

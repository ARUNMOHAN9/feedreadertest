# Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.

## Instructions

1) Extract the zip file
2) Open index.html
3) All test results will be shown at the bottom of the test page.

## Test suites included

1) RSS Feeds

2) The menu

3) Initial Entries

4) New Feed Selection


### Tests

**RSS Feeds**

a) _are defined_ : tests to make sure that the allFeeds variable has been defined and that it is not empty. Can be tested by tweaking allFeeds variable.

b) _URLs are defined_ : loops through each feed in the allFeeds object and ensures it has URL defined which is not empty. Can be tested by modifying the url key in the allFeeds array.

c) _names are defined_ : loops through each feed in the allFeeds object and ensures it has name defined which is not empty. Can be tested by modifying the ame key in the allFeeds array.

**The menu**

a) _is hidden by default_ : test that ensures the menu element is hidden by default. Can be tested by removing class 'menu-hidden'.

b) _changes visibility when menu icon is clicked_ : Ensures proper working of toggle menu.  Can be tested by modifying class 'menu-hidden'.

**Initial Entries**

a) _feed container has atleast 1 entry_ : ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
Can be tested by not adding anything to the .feed container.

**New Feed Selection**

a) _feed content changes_ : ensures when a new feed is loaded by the loadFeed function that the content actually changes. Can be tested by making feed contents same which fails the test.


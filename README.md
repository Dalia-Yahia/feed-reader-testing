# Project Overview

My task was to complete adding testing steps through the application since its developer had to move on to start own business. This project concerns only on testing and how to implement it through developing.

## How I completed this project

I was tasked to write the following tests in different test suites. Some tests required asynchronous function so I used callbacks - the `done()` argument within call to `beforeEach()`

1. A test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
2. A test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
3. A test that ensures the menu element is hidden by default under "The Menu" test suite.
4. Test that ensures the menu changes visibility when the menu icon is clicked.
5. A test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry`element within the `.feed` container.
6. A test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes

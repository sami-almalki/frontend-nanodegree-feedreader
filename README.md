Feed Reader Testing
========================

This is a web-based application for reading RSS feeds, that has [Jasmine](http://jasmine.github.io/) Testing library included. The goal from this project is to use testing as part of the development process.

## Usage

To see or modify the project's test units:
1. Download or clone the repository from [here](https://github.com/sami-almalki/frontend-nanodegree-feedreader).
2. To test the project, open `index.html`.
3. To modify the test units, go to `./jasmine/frontend-nanodegree-feedreader/jasmine/spec/` and open `feedreader.js`

## Unit Tests Included

The project has 7 test units to test 4 parts of the project functionality:

1. RSS Feed:

  * Ensures that `allFeeds` variable in `./js/app.js` is defined.
  * Ensures that `allFeeds` object has a URL defined and that the URL is not empty.
  * Ensures that `allFeeds` object has a name defined and that the URL is not empty.

2. The menu:

  * Ensures that the menu element is hidden by default.
  * Ensures that the menu changes visibility when its icon is clicked.

3. Initial Entries:

  * Ensures that the initial entries should be loaded correctly.

4. New Feed Selection:

  * Ensures that the new feed Selection is changing the content.

## Live Demo

[Click here to give it a try!](https://sami-almalki.github.io/frontend-nanodegree-feedreader/index.html)

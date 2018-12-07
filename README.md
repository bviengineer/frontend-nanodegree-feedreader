## Project Overview
This project consists of a web-based application that reads RSS feeds and uses Google's RSS API. In its original state, it included Jasmine and an initial test suite! I added comprehensive unit tests to ensure:

* The name and URL for each feed are not blank or missing
* The menu element is hidden by default and toggles between open and close when clicked
* The initial feeds loaded are unique and are not duplicates, using asynchronous testing methods

## Access to Project
* Clone the repository and open the index.html file in your browser
* Alternatively, download the project as a zip file, unzip the folder and open the index.html file in your browser

## Takeaway
* Writing test using the Red, Green, Refactor (TDD) methodology, provides the benefit of understanding whether new code will break or will not have any affect on [a] feature(s).

## Credits
The following sources proved helpful during the development of this project:
1. [Matthew Cranford's Blog](https://matthewcranford.com/feed-reader-walkthrough-part-4-async-tests/)
2. [PlaySnowi GitHub Repository](https://github.com/PlaySnowi/Feed-Reader-Testing/blob/master/jasmine/spec/feedreader.js)

## Project Origin
* [Udacty](https://github.com/udacity/frontend-nanodegree-feedreader)
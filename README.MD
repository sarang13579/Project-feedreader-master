1. First download the starter code for Feed Reader Testing  application.
2. Familiarize with the HTML, CSS, JS and Jasmine files provided.
3. Open the index.html file in browser and observe the webpage functionality and to get a better understanding of the code.
4. Open the jasmine spec file from jasmine folder. The first step of testing the feeds url and name is provided.
5. Open app.js file and familiarize how webpage handles menu element and the feeds using classes.
6. Observe the first test suite already present in starter code of jasmine spec file. Make the test fail by editing the app.js file allFeeds variable as null which ensures that the variable is not empty.
7. Write a new test suite named "The menu". Analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
8. Write a test that ensures the menu element is hidden by default by assigning menu-hidden class is to be true and reappears when menu icon clicked by triggering click event of the menu-icon-link class of anchor element. 
9. Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
10. Write a test suite named `"Initial Entries" whose test ensures .entry element within the .feed container is not empty by length of feed greater than 0.
11. Write a test suite named `"New Feed Selection"`.
12. Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.


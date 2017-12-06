

To run this project:

1. clone/download the directory
2. open directory
3. open index.html in your browser locally.
4. It will be displyed if there is no failure in green


How test was done?

1. 'RSS Feeds' will test that allFeeds var are defined and not empty
    1.1 'has a URL defined' Loop through each feed to ensure that url has been defined and not empty
    1.2 'has a name defined Loop through each feed to ensure that name has been defined and not empty

2. 'The menu' will test the menu to ensure visibility feature changes when clicked     (hide/show)
    2.1 'menu element is hidden' will ensure menu is hidden by default
    2.2 'menu shows and hides when clicked' will ensure menu visibility will change once it's clicked


3. 'Initial Entries'
    3.1 beforeEach ensure loadFeed() is async
    3.2 'function is called and has at least a single feed' ensures the function is called and there is only one .entry in .feed.


4. 'New Feed Selection' test
    4.1 beforeEach ensure loadFeed() is async
    4.2 'content will change once a new feed is loaded' ensures the content will change once feed is loaded

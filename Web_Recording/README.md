# Web_Recording
Web Recording is similar to desktop recording like searching on web, clicking options (elements) etc. For this installing UiPath Browser extension is required.

### 01-Opening_a_Webpage.xaml
-This sequence is designed to open a webpage. For this open webpage activity is used, in which we need to specify the browser type (application name) and also the web address of the website.

### 02-Searching_Google_for_a_Query.xaml
-In this sequence input dialog box is used to get user input (query) and stored it in a variable, later this variable is carried forward to open webpage activity which will open 'www.google.com' and using typeinto activity user input is typed to search box and using attribute of typeinto 'Enter' button is also pressed virtually by bot to search the query.

### 03-Searching_Wikipedia_for_a_Query.xaml
-In this sequence input dialog box is used to get user input (query) and stored it in a variable, later this variable is carried forward to open webpage activity which will open 'www.wikipedia.org' and using typeinto activity user input is typed to search box and using attribute of typeinto 'Enter' button is also pressed virtually by bot to search the query.
# Web_Recording
Web Recording is similar to desktop recording like searching on web, clicking options (elements) etc. For this installing UiPath Browser extension is required.

### 01-Opening_a_Webpage.xaml
- This sequence is designed to open a webpage. For this open webpage activity is used, in which we need to specify the browser type (application name) and also the web address of the website.

### 02-Searching_Google_for_a_Query.xaml
- In this sequence input dialog box is used to get user input (query) and stored it in a variable, later this variable is carried forward to open webpage activity which will open 'www.google.com' and using typeinto activity user input is typed to search box and using attribute of typeinto 'Enter' button is also pressed virtually by bot to search the query.

### 03-Searching_Wikipedia_for_a_Query.xaml
- In this sequence input dialog box is used to get user input (query) and stored it in a variable, later this variable is carried forward to open webpage activity which will open 'www.wikipedia.org' and using typeinto activity user input is typed to search box and using attribute of typeinto 'Enter' button is also pressed virtually by bot to search the query.

### 04-FillingGoogleForm.xaml
- This sequence is created for filling up google form multiple times with the available data stored in excel. In this sequence open browser is used to open google form. Later on excel application scope is used to specify the excel file which contains data, later on for each row is used under which different assign activities is used to assign cell values from excel file to string type variables, these variables are carried to typeInto activities which will type data from these variables to various specified fields of google form. After filling each response it will click on submit another response option and start over & keeps on repeating till end.
01-Creating_DataTable_and_OutputDataTable
-Build data table activity is used to create (bulid) a data table, it is similar to excel with rows & coulmns and used to store data in the form of different data type like int32, string etc. In this sequence data table is created by user, that store some user entered data. Later this build data table is assigned a variable of data table type which is carried forward to output data table activity that will read the data from pre-defined data table and will convert it to string with comma seperation with respect to each column & store it in another variable of string data type & this variable is carried forward to write line activity to print the output.

02-Using_ForEachRow.xaml
-In this sequence a pre-defined data table is created using Build data table activity & stored in a variable of data table data type. This variable is carried forward to a for each row activity using which we can seperate data of each row and send print them individualy.

03-WritingToExcel_from_DataTable.xaml
-In this sequence again a pre-defined data table is created using Build data table activity & stored in a variable of data table data type. This variable is carried forward to a excel application scope activity where using a write range activity data values from data table (from UiPath application) is stored in mentioned excel file.
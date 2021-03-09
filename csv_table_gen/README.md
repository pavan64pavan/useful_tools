# CSV File - SQLITE TABLE

This tool is built to help Analysts perform SQL analytics on a CSV file.  

Ideally, if one has to perform analytics on a CSV file, a table has to be created and the data within the CSV file has to be inserted into the corresponding table with the help of a Data Engineer.

The idea behind this tool was to avoid that step, help Analysts perform analytics without any intervention and more importantly, without any extra cost.

This tool, reads the CSV file with a Header, creates a Database file (if it does not exist in a given directory already), creates a Table with the specified Table Name and finally inserts all the data into the Table.

I recommend using a file less than 1GB for processing using this tool.

**Instructions**

1. Extract the .exe file from the ZIP file csv_table_gen_fe.zip.
2. Run the csv_table_gen_fe.exe file, a GUI window appears within a  minute or so.
3. Browse the file, please select a CSV File with Column Header. The Column Header will be used for creating the Table. 
4. Enter a preferred Database Name. The tool creates a '.db' file within the same directory as input file. It exits with an ERROR Message if the Database Name is blank.
5. Enter the required Table Name and click on Submit. The tool exits with an ERROR Message if the Table Name is blank.
6. If the data is in hundreds of MBs, it will take few minutes to complete the process. The print statements in the Console should display 'Data Insertion in Progress...'
7. Once the Data Insertion is complete, a INFO window dialog box appears with a SUCCESS message. The Database file should be created 

**Data Analytics**

1. Install "SQLite Studio Open Source" to perform Analytics on the Data.
2. Open SQLite Studio.
      Select Database -> Add Database
      Browse to the directory where the database file is created and select the “.db” file
3. A table should be created in the Database.


**Processing**

1. The tool uses SQLITE database.
2. Database will be created as a file with an extension ".db". If the file exists in the directory, it uses the same.
3. The Table will be created in the Database. And, the data will be inserted part by part.
4. If the table exists, the data will be appended.

**Recommendations**

* Please process files less than 1 GB. 
* Ensure that the table does not exist already in the Database.
* If you want to append data to an existing table, please get in touch with me on my email pavan64pavan@gmail.com

**Suggestions & Feedback**

* Please email me on pavan64pavan@gmail.com with the keyword CSV_Table_Gen in the Subject line.

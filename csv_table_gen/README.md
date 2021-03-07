# CSV File - SQLITE TABLE

This tool is built to help Analysts perform SQL analytics on a CSV file.  

Ideally, if one has to perform analytics on a CSV file, a table has to be created and the data within the CSV file has to be inserted into the corresponding table with the help of a Data Engineer.

The idea behind this tool was to avoid that step, help Analysts perform analytics without any intervention and more importantly, without any extra cost.

This tool, reads the CSV file with a Header, creates a Database file (if it does not exist in a given directory already), creates a Table with the specified Table Name and finally inserts all the data into the Table.

I recommend using a file less than 1GB for processing using this tool.

**Instructions**

1. Extract the .exe file from the ZIP file csv_table_gen_fe.zip - Please select a File with Column Header.
2. Run the csv_table_gen_fe.exe file, a GUI window appears
3. Browse the file
4. Enter a preferred Database Name.
5. Enter the required Table Name and click on Submit.
6. Install "SQLite Studio Open Source" to perform Analytics on the Data.
7. Open SQLite Studio.
      Select Database -> Add Database
      Browse to the directory where the database file is created and select the “.db” file
8. A table should be created in the Database.


**Processing**

1. The tool uses SQLITE database.
2. Database will be created as a file with an extension ".db". If the file exists in the directory, it uses the same.
3. The Table will be created in the Database. And, the data will be inserted part by part.
4. If the table exists, the data will be appended.

**Recommendations**

* Please process files less than 1 GB.
* Ensure that the table does not exist already in the Database.
* If you want to append data to an existing table, please get in touch with me on pavan64pavan@gmail.com

Farmer-Expenses-Harvest-and-Profit-Analyzer-for-Rice-and-Vegetables-In-Pakil-Laguna
105 FINAL PROJECT

Main Menu:

<img width="353" height="156" alt="Capture" src="https://github.com/user-attachments/assets/7d7ead10-9841-4a8d-ad09-0cf9bdccc5c2" />

This is the Main Menu of the system. It displays the list of available function that the users can choose from:
 1 -  Record Expenses
2 - Record Harvest
3 - Generate Summary Report
4 - Export Database to Excel/CSV
5 - Exit
Select an option (1-5):
If name main: is the entrance of the program. This code block ensures that the main_menu() function will only execute if the file is executed directly by Python.

2.Record Expenses Module:

<img width="326" height="109" alt="Capture2" src="https://github.com/user-attachments/assets/360e895f-b70c-42b1-b204-50c2ce5281dc" />

The add_expense() function allows for adding new information regarding expenses made in the farm. Users should provide the name of the expense category and its value, while the date will be added automatically. Information provided will be inserted in the expenses table within the database. This function contains error prevention options. This function records information regarding harvested crops. Users provide the name of the crop that has been harvested, harvest weight in kilograms, and its price per kilogram. All this information along with the current date will be recorded in the harvests table.

3.Record Harvest Module:

<img width="380" height="126" alt="Capture3" src="https://github.com/user-attachments/assets/12f6fbf7-bfa7-4ac4-8199-a6bb5d5b9127" />

This module records harvest information. The user inputs the crop name and  yield in kg and price per kg. After saving a confirmation will appear.  And the information will automatically save in the database.


4. Generate Summary Report Module

<img width="545" height="376" alt="image" src="https://github.com/user-attachments/assets/f130840d-5f74-4042-b40b-1305a86ab70f" />

This module generates the summary report. It shows:
-Itemized Expense
-Itemized Harvest
-Total Expenses
-Total Harvest
-Net profit or loss
The report generation function will enable the users to assess the financial status of the farm and determine its profit or loss situation.

5.Export Databased to CSV module

<img width="642" height="79" alt="image" src="https://github.com/user-attachments/assets/5a091c7b-2b6b-488a-9b86-7d85491c54aa" />

This module exports the data from the database into two CSV files.
- farm_expenses.csv
- farm_harvest.csv
These files can be opened to Microsoft Excel or any spreadsheet application.

6. Exit Module

<img width="317" height="98" alt="image" src="https://github.com/user-attachments/assets/773c7b76-568c-46f7-b1ca-181a4f464609" />

This module closes the system and ends the program.


LINKS:

Interview: 
https://drive.google.com/file/d/1aORpjMefG-R2sY5OLH_7RSlU5SkxcCyj/view?usp=drive_link





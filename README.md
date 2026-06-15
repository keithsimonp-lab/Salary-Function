# Salary-Function - Jupyter Notebook

In this project we explore and analyze employee salary data.I load data, find specific employee information, process salaries, and export data.

Getting Started
To use this notebook, you first need to upload the Total.csv file, which contains all the employee data.

Upload Total.csv: Run the cell below to upload your data file. A pop-up window will appear, allowing you to select Total.csv from your computer. 

1. Load and Inspect Data
These cells load the Total.csv file into a pandas DataFrame (like a smart spreadsheet) and display basic information about it. This helps you see what kind of data you're working with.

2. Get Employee Details
This section defines a function get_employee_details that allows you to quickly find all information for a specific employee by their full name. Remember that the name is case-sensitive!

3. Process Employee Data into a Dictionary
Here, the DataFrame is converted into a Python dictionary called employees. This makes it easier to access individual employee records using their name as a key. It also calculates and prints the total salary and individual salaries, along with employee names and job titles.

4. Export Employee Profile
This part of the code takes the data for the first employee in the dataset, creates a CSV file named employee_profile.csv with their details, and then zips it into Employee Profile.zip. This is useful if you want to share or save a single employee's record.

5. Check and Download Files
These cells help you verify that the files were created in your Colab environment and then provide a way to download them directly to your local computer.

-------------------------------------------------------------------------------------------------------------------------

# How to Use the R Script to Unzip and Display Employee Data - R
OVERVIEW
This script is used to extract employee data from a zipped folder and display it in R.  
The data was originally created in Python, exported as a CSV file, and saved inside a ZIP file.

REQUIRED FILES
Before running the script, make sure you have:
- EmployeeProfile.zip

Important:
The ZIP file must be in the same folder where your R script is running.

STEPS TO FOLLOW

Step 1: Confirm Working Directory
The script checks where R is looking for files.
This tells you where your ZIP file should be located.

Step 2: Check Available Files
The script lists all files in the working directory.
Make sure EmployeeProfile.zip appears in this list.

Step 3: Set ZIP File Name
The script uses EmployeeProfile.zip as the file name.
Ensure the name has no spaces and matches exactly.

Step 4: Unzip the File
The script extracts the ZIP file into a folder called EmployeeProfile1.
This folder is created automatically.

Step 5: Check Extracted Files
The script checks what files are inside EmployeeProfile1.
You should see your CSV file (e.g., employeeprofile.csv).

Step 6: Load the CSV File
The script reads the CSV file from inside the extracted folder.
This loads the employee data into R.

Step 7: Display the Data
The script prints the employee data in the R console.
You should see names and salary values.


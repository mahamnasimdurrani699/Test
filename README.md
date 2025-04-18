# Data Analysis Project

This project contains Python code for performing data analysis tasks using the `numpy` and `pandas` libraries.

## Contents

### Question 1: 5-Number Summary Calculation
-  Calculates the 5-number summary (minimum, first quartile, median, third quartile, and maximum) of a given dataset using `numpy`.

### Question 2: Employee Data Analysis
-  Performs various data analysis operations on employee data using `pandas`, including:
    -   Grouping data by department and calculating average attendance.
    -   Filtering employees based on attendance and grouping them by department.
    -   Finding average and maximum salary per department.
    -   Identifying employees in the IT department with above-average attendance.
    -   Calculating total salary paid per department.
    -   Finding employees in each department with above-average attendance using `groupby()` and `apply()`.

### Question 3: Data Cleaning and Preprocessing
- Performs data cleaning and preprocessing on a dataset with missing and inconsistent values, including:
    -   Removing duplicate records.
    -   Handling missing values in 'Name', 'JoinDate', and 'Salary' columns.
    -   Converting the 'JoinDate' column to datetime format.
    -   Standardizing the 'Department' column values.
    -   Dropping rows with missing or invalid 'EmpID' values.

## Libraries Used
-   numpy
-   pandas

## How to Run
1.  Ensure you have Python installed.
2.  Install the required libraries: `pip install numpy pandas`
3.  Run the Python script.

## Input Data
-   The script uses hardcoded data for demonstration purposes.  For Question 1, the data is: `[35, 45, 56, 62, 68, 72, 78, 85, 89, 94, 100]`.
-  For Questions 2 and 3, the data is in dictionary format and then converted into a pandas DataFrame.

## Output
The script prints the results of each analysis step to the console.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

# SW_Testing_Project
This is to complete requirements for the SWE-6673 Software Testing and Verification project.

# Program Dependency
Requires the following languages or extensions to run:
1. Python v3.10.x or higher
2. Jupyter Extension (if using VSCode) or ability to run Jupyter notebooks
3. Python Extension (if using VSCode) 

## How to Run Project
1. Open the SBFL Jupyter notebook and scroll to the bottom of the page. 
2. Change 1st input of the Create_Ranked_Lists function to the number of false tests desired (min 0, max 2262)
3. Change 2nd input of the Create_Ranked_Lists function to the name of the suspicion report  (default = "test_report")
3. Select Run All

## Program Output
The program outputs the results of the ranked lists for all 4 SBFL suspicion algorithms (Tarantula, SBI, Jaccard, and Ochiai) and list of falsified tests in the suspicion_reports/selected_report_name directory 

The program creates an unsorted version of the suspicion calculation information in a Python dictionary within the Create_Ranked_Lists function, but saving those results were deemed outside the scope of this project. 

All of the information can be found and printed from the variables in the Create_Ranked_Lists function however

## Implementation Notes
One noteworthy feature of the project is that a system for randomly selecting a user-determined number of tests to fail is incorporated into the program's functionality. After each test run-through, the tests are returned to their original true state.
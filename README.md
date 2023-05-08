# SW_Testing_Project
This is to complete requirements for the SWE-6673 Software Testing and Verification project.

# Program Dependenc

## How to Run Project
1. Open the SBFL Jupyter notebook and scroll to the bottom of the page. 
2. Change input of the Create_Ranked_Lists function as desired (min 0, max 2262)
3. Select Run All

## Program Output
The program outputs the results of the ranked lists for all 4 SBFL suspicion algorithms (Tarantula, SBI, Jaccard, and Ochiai) in the suspicion_reports directory with a title corresponding to the time of creation. 

The program creates an unsorted version of the suspicion calculation information in a Python dictionary within the Create_Ranked_Lists function, but saving those results were deemed outside the scope of this project. 

All of the information can be found and printed from the variables in the Create_Ranked_Lists function however

## Implementation Notes
One noteworthy feature of the project is that a system for randomly selecting a user-determined number of tests to fail is incorporated into the program's functionality. After each test run-through, the tests are returned to their original true state.
# Academic Tracker 
Name - Anshika Maheshwari
Reg No. - 25BCE10595
Course : CSE1021 - Problem Solving and Python Programming 
This is a small project that helps a student to track assignments,grades and overall performance.
This project also promotes accountability and better planning. It's practical for real-life education, using standard libraries for calculations, persistence, and date handling.
#Overview
This project is developed in jupyter notebook to help students keep track of their assignments, due dates, and grades. Instead of relying on scattered notes or forgetting important deadlines, students can store everything in one place and even get their GPA calculated automatically. The program saves data for future use, reminds users of overdue tasks, and keeps academic records organized using just four standard Python libraries. It’s a practical, everyday tool meant to make student life easier and more manageable.
#Requirement Analysis
Functional analysis-
Add assignments with name, due date, and grade.
Calculate GPA and show performance reports.
Display pending and overdue tasks.
Save and load data within the notebook.
Non-Functional analysis-
Easy to use in Jupyter Notebook.
Clear, organized code cells.
Uses only standard libraries (statistics, pickle, datetime, os).
Portable and works on any system with Jupyter.
#Technologies/tools used 
Python: Core programming language used to build the entire tracker.
Jupyter Notebook: Interactive environment for writing, running, and testing the code step-by-step.
Standard Python Libraries:
statistics for GPA calculation
pickle for saving and loading data
datetime for handling due dates
os for file checking and management
Markdown: Used for documenting the project inside the notebook and repository.
#Steps to install and run the programs
1.Install Python and Jupyter Notebook.
2. Open the notebook where the code is written.
3. Run the import cell to load statistics, pickle, datetime, and os.
4. Run the cell that loads/saves data to initialize the assignment list.
5. Run the menu cell and follow the options to add assignments, calculate GPA, or view reports.
#Key Algorithms
When a student adds an assignment, the program collects the details, checks if the date is valid, and saves it safely for later use.
To calculate the GPA, the program gathers all the grades and simply finds their average.
For reports, it compares each assignment’s due date with today’s date to show which tasks are pending or overdue.
The system also checks if a saved file already exists and loads it, so the student’s data is always available.
#Implementation
The project is built in Jupyter Notebook using simple Python cells. It imports four standard libraries and uses functions to add assignments, calculate GPA, show reports, and save or load data. The notebook structure makes it easy to run each part step-by-step and clearly see the results.
#Library Usage Explanation
statistics: Computes mean for GPA calculations.
pickle: Handles data persistence.
datetime: Validates and compares dates.
os: Checks for file existence
# project report :-
[Programming.pdf](https://github.com/user-attachments/files/23711907/Programming.pdf)

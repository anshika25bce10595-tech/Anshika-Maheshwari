# Academic Tracker 
Name - Anshika Maheshwari
Reg No. - 25BCE10595
Course : CSE1021 - Problem Solving and Python Programming 
This is a small project that helps a student to track assignments,grades and overall performance.
This project also promotes accountability and better planning. It's practical for real-life education, using standard libraries for calculations, persistence, and date handling.
#Overview
This project is developed in jupyter notebook to help students keep track of their assignments, due dates, and grades. Instead of relying on scattered notes or forgetting important deadlines, students can store everything in one place and even get their GPA calculated automatically. The program saves data for future use, reminds users of overdue tasks, and keeps academic records organized using just four standard Python libraries. It’s a practical, everyday tool meant to make student life easier and more manageable.
#Requirement Analysis
Add assignments with name, due date, and grade.
Calculate GPA and show performance reports.
Display pending and overdue tasks.
Save and load data within the notebook.
Easy to use in Jupyter Notebook.
Clear, organized code cells.
Uses only standard libraries (statistics, pickle, datetime, os).
Portable and works on any system with Jupyter.
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


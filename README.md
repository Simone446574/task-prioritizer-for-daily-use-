# Smart Daily Task Prioritizer

Final project for the Building AI course  

## Summary
This AI that is built is to help improve efficiency and shows you which tasks need to take priority and in which order. 

## Background
People generally get overwhelmed an struggle to prioritize their daily tasks. This AI solves the following problems:  
  * Reduces fatigue coming from overthinking which tasks to prioritize.   
  * It allows the user to focus in the tasks at hand. 
* Motivation: I struggle to figure which tasks need o be prioritized and this is going to help take away that stress and allow me to move forward with work quicker. 
* Importance: This will improve time management for work.

## How is it used?
1. Create a CSV file (`tasks.csv`) with your daily tasks, and you must include the following columns: `task`, `duration_minutes`, `importance`, `deadline`.  
2. Run the Python script (`task_prioritizer.py`) in the same folder.  
3. The AI does a calculation on the priority and then displays them in correct order of importance.

Example CSV content:
```csv
task,duration_minutes,importance,deadline
Email reply,15,2,Today
Report draft,120,5,Tomorrow
Grocery shopping,60,1,Today
Team meeting,45,4,Today
Workout,30,3,Today
Read book,60,2,This week

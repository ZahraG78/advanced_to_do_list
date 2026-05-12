# advanced_to_do_list
Object Oriented Programming and Data Structures - ReadMe

Overview:

This project is a sophisticated Python task management system. It enables users to handle dependencies between activities while creating, managing, and organising them. Using graph-based algorithms, the system makes sure that jobs are finished in a valid order. 

Requirements:
Python 3.10+
No external libraries required


Key features:

Add Personal and Team Tasks
Task Dependency Management (Directed Graph)
Cycle Detection (prevents invalid dependencies)
Smart Task Scheduling (Topological Sort)
Priority-Based Sorting (Merge Sort)
Critical Path Analysis (longest dependency chain)
Task Completion Tracking
Simulation Mode (step-by-step execution)
Undo Function (stack-based)
File Saving (persistent storage)

Data structures used:

Linked List (task storage)
Stack (undo functionality)
Circular Queue (reminders)
Graph (task dependencies)

Algorithms used:

Depth-First Search (cycle detection)
Topological Sorting (task ordering)
Merge Sort (priority scheduling)
Dynamic Programming (critical path)

How to run:

Unzip the folder - this must be done. 

Make sure Python is installed (Python 3 recommended)
Open the project folder

Run the following command:

python main.py, or open the main.py file and run 

Follow the on-screen menu

Note: Task names must be entered exactly as created when marking tasks as complete.


Example Workflow:
1. Add Task "Design"
2. Add Task "Implementation"
3. Add Dependency Design → Implementation
4. View Smart Schedule

Known Limitations:
Task names are case-sensitive
Undo only supports task additions
Persistence currently stores basic task data only


FILES INCLUDED

main.py (main program)
task.py (task classes)
data_structures.py (linked list, stack, queue)
graph.py (dependency graph)
file_handler.py (save/load tasks)
utils.py (merge sort)

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/__oZ-IAL)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19822271&assignment_repo_type=AssignmentRepo)
# DSA-SEM-PROJECT-
DATA STRUCTURES AND ALGORITHMS SEMESTER PROJECT

**To-Do List Application
**
This is a simple To-Do List application built with Python and Tkinter. It allows users to manage their tasks, set priorities and difficulties, and stores the tasks in a database.

User Guide
Running the Application
Prerequisites: Ensure you have Python 3 and the mysql-connector-python library installed.

Database Setup:

SQLite (Default): The application will automatically create a my_tasks.db file in the src directory.

MySQL:

Open the src/main.py file.

Change the DATABASE_CHOICE variable to 'mysql'.

Update the mysql_config dictionary with your MySQL server details (host, user, password, and database).

Execution: Run the main.py script from the src directory to launch the application.

How to Use
Adding a Task:

Enter the task description in the "Description" field.

Select the priority (1-5) and difficulty (1-10) using the spinboxes.

Click the "Add Task" button.

Viewing Tasks: The main window displays a list of all tasks with their ID, description, priority, difficulty, status, and creation date.

Sorting Tasks:

Click "Sort by Priority" to order the pending tasks by their priority level.

Click "Sort by Difficulty" to order the pending tasks by their difficulty level.

Marking a Task as Complete:

Select a task from the list.

Click the "Mark as Complete" button.

Deleting a Task:

Select a task from the list.

Click the "Delete Selected" button.

Undo Last Action: Click the "Undo Last Action" button to revert the most recent create, update, or delete operation.

Show All Tasks: Click the "Show All" button to refresh the task list and display all tasks.

Features
Graphical User Interface: A user-friendly interface built with Tkinter for managing tasks.

Task Management: Create, delete, and update tasks with descriptions, priorities, and difficulties.

Data Persistence: Tasks are saved to a database, with support for both SQLite and MySQL.

Sorting:

Tasks can be sorted by priority using a Priority Queue.

Tasks can be sorted by difficulty using a Binary Search Tree.

Undo Functionality: The application uses a Stack to allow users to undo their last action.

Efficient Task Storage: A Hash Table is used for quick lookups, insertions, and deletions of tasks by their ID.

Status Bar: Provides feedback to the user about the status of their actions.

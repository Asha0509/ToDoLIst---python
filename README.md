# To-Do List Application

## Overview
This is a simple To-Do List application built using Python and Tkinter for the graphical user interface (GUI). It allows users to add, delete, and manage tasks. The tasks are stored in an SQLite database for persistence.

## Features
- **Add Tasks**: Users can enter a task and add it to the list.
- **Delete Tasks**: Users can remove a selected task from the list.
- **Delete All Tasks**: Users can clear the entire task list.
- **Persistent Storage**: Tasks are stored in an SQLite database, ensuring they remain available even after the application is closed.

## Requirements
- Python 3.x
- Tkinter (comes pre-installed with Python)
- SQLite3 (comes pre-installed with Python)

## Installation
1. Clone the repository or download the script.
   ```sh
   git clone https://github.com/your-repository/todo-list.git
   ```
2. Navigate to the project directory.
   ```sh
   cd todo-list
   ```
3. Run the script.
   ```sh
   python todo_list.py
   ```

## Usage
1. Run the script to open the To-Do List application.
2. Enter a task in the input field and click **Add** to save it.
3. Select a task and click **Remove** to delete it.
4. Click **Delete All** to remove all tasks.
5. Click **Exit / Close** to close the application.

## File Structure
- `todo_list.py` - Main script containing the application logic.
- `listOfTasks.db` - SQLite database file (automatically created).

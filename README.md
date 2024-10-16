# Task Manager CLI Application

## Overview
This project is a Python-based **Command-Line Interface (CLI) Task Manager** that allows users to manage tasks easily. The application provides options to add, view, delete, and mark tasks as complete. Task data is saved and loaded from a JSON file (`tasks.json`) to ensure persistence between sessions.

## Features
- **Add Task**: Users can add new tasks with unique IDs and titles.
- **View Tasks**: Users can view all tasks with their status (completed or not).
- **Delete Task**: Users can remove tasks by their ID.
- **Mark Task as Complete**: Users can mark tasks as completed by their ID.
- **Save and Load Tasks**: Tasks are saved to and loaded from a JSON file to maintain progress.
  
## Project Structure
- `task_manager.py`: Main Python file that contains the task management logic.
- `tasks.json`: (Generated during runtime) Stores tasks data in JSON format.

## How to Use
Once the application is running, you will be presented with a menu of options:
1. Add a task
2. View all tasks
3. Delete a task
4. Mark a task as complete
5. Save and exit

Follow the on-screen prompts to manage your tasks.

### Example:
- To add a task, enter `1` and then provide a title for your task.
- To view all tasks, select `2`, and the list of tasks will be displayed.
- To delete a task, select `3` and enter the task ID to remove it.

## Requirements
- Python 3.x
- JSON support (comes with Python)

## Future Enhancements
- Implement a search/filter feature to view tasks by status (completed/pending).
- Add support for task editing (update task title).
- Improve task categorization and prioritization.

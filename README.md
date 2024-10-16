# Task Manager CLI Application
## Overview
This project is a Python-based Command-Line Interface (CLI) Task Manager that allows users to manage tasks easily. The application provides options to add, view, delete, and mark tasks as complete. Task data is saved and loaded from a JSON file (tasks.json) to ensure persistence between sessions.
## Features
**Add Task**: Users can add new tasks with unique IDs and titles.
**View Tasks**: Users can view all tasks with their status (completed or not).
**Delete Task**: Users can remove tasks by their ID.
**Mark Task as Complete**: Users can mark tasks as completed by their ID.
**Save and Load Tasks**: Tasks are saved to and loaded from a JSON file to maintain progress.
## Project Structure
**task_manager.py**: Main Python file that contains the task management logic.
tasks.json: (Generated during runtime) Stores tasks data in JSON format.

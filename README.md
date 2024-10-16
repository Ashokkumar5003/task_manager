# 📝 Task Manager CLI Application

A simple yet efficient **Command-Line Interface (CLI) Task Manager** built in Python. This tool helps users manage tasks by adding, viewing, deleting, and marking them as complete. With built-in file handling, your tasks are saved and loaded automatically from a JSON file, ensuring your progress is never lost.

## 🚀 Features
- **🆕 Add Tasks**: Create new tasks with unique IDs and titles.
- **👀 View Tasks**: Display all tasks along with their status (completed or not).
- **❌ Delete Tasks**: Remove tasks by their ID from the task list.
- **✅ Mark as Complete**: Update tasks as completed using their ID.
- **💾 Save & Load**: Tasks are persisted to a JSON file for future sessions.

## 📂 Project Structure
```
task_manager_cli/
│
├── task_manager.py      # Main Python script containing the task manager logic
├── tasks.json           # (auto-generated) JSON file storing tasks
└── README.md            # Documentation for the project
```

## ⚙️ Installation

### 1. Clone the Repository:
```bash
git clone https://github.com/yourusername/task_manager_cli.git
```

### 2. Navigate to the Project Directory:
```bash
cd task_manager_cli
```

### 3. Run the Application:
```bash
python task_manager.py
```

## 🎮 How to Use
Once launched, the application will guide you through managing your tasks via a simple menu.

```bash
Task Manager Menu:
1. Add a Task
2. View Tasks
3. Delete a Task
4. Mark Task as Complete
5. Save and Exit
```

#### Example Workflow:
- **Adding a Task**: Choose option `1`, enter the task title, and the task will be added to your list.
- **Viewing Tasks**: Choose option `2` to see all your tasks with their completion status.
- **Marking as Complete**: Select option `4`, and enter the task ID to mark it as done.
- **Deleting a Task**: Select option `3` and provide the task ID to remove it from the list.

## ⚙️ System Requirements

- **🐍 Python 3.x**: Ensure you have Python installed on your system. You can download the latest version from [python.org](https://www.python.org/downloads/).
- **💻 Code Editor**: Use a modern code editor for development, such as:
  - [**PyCharm**](https://www.jetbrains.com/pycharm/) for a feature-rich Python IDE.
  - [**Visual Studio Code**](https://code.visualstudio.com/) for a lightweight yet powerful editor.
  

## 💡 Future Enhancements
- **Task Search**: Filter tasks by status (completed, pending).
- **Task Editing**: Ability to edit the title of existing tasks.
- **Task Categorization**: Add support for task categories and prioritization levels.
- **User Authentication**: Add real user login and session management features.

## 👤 Dummy Login Credentials
For testing purposes, a dummy login system is provided. Use the following credentials:

- **Email**: `testuser@example.com`
- **Password**: `password123`

## 💡 Contributing

We welcome contributions! If you’d like to add new features, fix bugs, or improve documentation, feel free to fork the project and create a pull request.

### Steps to Contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

---

## 👤 Author

**Ashok kumar S**  
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [your-linkedin-profile](https://linkedin.com/in/yourprofile)

---

### 🎉 Thank you for checking out this project! Happy task managing! 🎉

---

This README is designed to **grab attention** with the use of **emojis**, **badges**, and a **well-structured layout**. It incorporates:
- **Clear instructions** on installation and usage.
- **Feature highlights** for quick insights.
- **Contribution guidelines** to welcome developers.
- **Future enhancements** to show the project’s potential.




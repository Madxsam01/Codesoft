# Codesoft 🚀

Welcome to my **Codesoft Python Internship** repository! This project contains three Python-based GUI applications built using standard libraries to solve practical, everyday tasks

## Badges 🛡️

| Build Status | Version | License |
|--------------|---------|---------|
| ![Build Status](https://img.shields.io/badge/build-passing-brightgreen) | ![Version](https://img.shields.io/badge/version-1.0.0-blue) | ![License](https://img.shields.io/badge/license-MIT-red) |

## Table of Contents 📜

- [Project Title & Badges](#codesoft-🚀)
- [Description](#description)
- [Features](#features-✨)
- [Tech Stack](#tech-stack-💻)
- [Installation](#installation--)
- [Usage](#usage--)
- [Project Structure](#project-structure-📁)
- [Contributing](#contributing-🤝)
- [License](#license-📝)
- [Important Links](#important-links-🔗)
- [Footer](#footer-💖)

## Description

It provides a set of utility applications designed for everyday use:

- **Password Generator:** A tool to create strong, random passwords of a specified length.
- **To-Do List:** An application to manage tasks, allowing users to add, mark as completed, and delete tasks. Tasks are persisted locally using a `tasks.json` file.
- **Simple Calculator:** A basic calculator with arithmetic operations.

These applications are built with a focus on simplicity and ease of use, leveraging Python's standard libraries for GUI development and task management.

## Features ✨

- **Password Generator:**
  - Generate random passwords with customizable length.
  - Includes uppercase letters, lowercase letters, digits, and punctuation.
- **To-Do List:**
  - Add new tasks with descriptions.
  - Mark tasks as completed.
  - Delete existing tasks.
  - Persists tasks to `tasks.json` for session continuity.
  - User-friendly graphical interface.
- **Simple Calculator:**
  - Basic arithmetic operations (+, -, *, /).
  - Handles input and displays results.
  - Includes error handling for invalid expressions.

## Tech Stack 💻

- **Language:** Python
- **GUI Toolkit:** Tkinter
- **Data Persistence (To-Do List):** JSON
- **Libraries:** `string`, `random`, `json`, `os`

## Installation 🛠️

This project requires Python to be installed on your system. Since it uses standard Python libraries, there are no external dependencies to install.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Madxsam01/Codesoft.git
   cd Codesoft
   ```

2. **Run the applications:**
   You can run each application directly from the command line.

   - **Password Generator:**
     ```bash
     python Password_generator.py
     ```

   - **To-Do List:**
     ```bash
     python To_Do_List.py
     ```
     *(This will create a `tasks.json` file in the same directory to store your tasks.)*

   - **Simple Calculator:**
     ```bash
     python calculator.py
     ```

## Usage 💡

Each Python file in the repository represents a standalone application. You can launch them independently to perform their respective functions.

### Password Generator 🔑

1. Run `python Password_generator.py`.
2. Enter the desired length for your password in the input field.
3. Click the "Generate Password" button.
4. The generated password will be displayed.

### To-Do List 📝

1. Run `python To_Do_List.py`.
2. Enter a task description in the input field.
3. Click "Add Task" to add it to the list.
4. Select a task from the list and click "Mark as Completed" to mark it.
5. Select a task and click "Delete Task" to remove it.
6. Tasks are automatically saved to `tasks.json` and loaded when the application starts.

### Simple Calculator 🧮

1. Run `python calculator.py`.
2. Use the buttons to input numbers and operators.
3. Press the "=" button to evaluate the expression.
4. The result will be displayed in the entry field.
5. "Error" will be displayed for invalid operations.

## Project Structure 📁

The project consists of the following files:

```
Codesoft/
├── README.md
├── Password_generator.py
├── To_Do_List.py
└── calculator.py
```

- `README.md`: This file, containing project information and instructions.
- `Password_generator.py`: Python script for the password generation GUI.
- `To_Do_List.py`: Python script for the To-Do list GUI application, including task persistence.
- `calculator.py`: Python script for the simple calculator GUI.

## Contributing 🤝

Contributions are welcome! If you have suggestions for improvements or new features, please feel free to:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'
`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a Pull Request.

## License 📝

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. (Note: A LICENSE file was not found in the repository analysis, assuming MIT based on common practice for such projects).

## Important Links 🔗

- **Repository URL:** https://github.com/Madxsam01/Codesoft

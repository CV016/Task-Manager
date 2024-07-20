# Task-Manager

## Intelligent Task Manager in C++

This project implements an intelligent task manager application written in C++. It prioritizes tasks based on their deadlines and completion status, helping you stay organized and manage your workload effectively.

### Features

* **Task Management:** Add, delete, and view tasks with detailed information like name, description, deadline, and completion status.
* **Priority Calculation:** Tasks are prioritized based on a custom formula that considers both deadline and completion status. Tasks nearing deadlines and incomplete tasks receive higher priority.
* **Dependency Management (Not currently implemented):** (Optional) Tasks can be linked to other tasks as dependencies, ensuring a specific order of execution.
* **User Interaction:**  A text-based interface allows users to interact with the program by adding, deleting, viewing, and completing tasks. 

### Getting Started

This project requires a C++ compiler and basic understanding of C++ data structures and algorithms.

1. **Clone the Repository:** (If using Git)
```
git clone https://<your_repository_link>.git
```

2. **Compile the Code:**
   The specific compilation command will vary depending on your compiler. However, a typical example might be:
   ```bash
   g++ [file_name].cpp -o task_manager
   ```
   This will create an executable file named "task_manager".

3. **Run the Program:**
   ```bash
   ./task_manager
   ```

### Usage

The program provides a menu-driven interface that allows you to manage your tasks. 

* **Add Task:** Enter the task details, including name, description, deadline, and dependencies (currently not implemented).
* **Delete Task:** Provide the name of the task to remove it.
* **View Tasks:** View a list of all tasks with their current priority, completion status, and other details.
* **Mark Task Completed:** Update the completion status of a specific task (currently commented out).
* **Exit:** Terminate the program.


### Tools and Technologies

* Programming Language: C++
* Data Structures: unordered_map, priority_queue, list
* Algorithms: Custom Priority Calculation (Topological Sorting - Not currently implemented)
* User Interface: Text-based (Optional: GUI can be implemented)

### Future Enhancements

* Implement topological sorting to enforce task execution order based on dependencies.
* Improve error handling for user input and memory allocation.
* Add persistence functionality to save and load tasks from a file.
* Develop a more user-friendly graphical user interface (GUI).

### Contributing

We welcome contributions to this project! If you have any suggestions or improvements, feel free to fork the repository and submit a pull request.

This README file provides a basic overview of the intelligent task manager application. For detailed information about the code, functionalities, and potential improvements, please refer to the source code files within the project directory.

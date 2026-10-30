# Simple Java Task Manager

A beginner-friendly, menu-based task manager built using core Java. It lets a user add, view, complete, and delete tasks. Tasks are saved in a local text file, so they are still available after the program is closed.

## Features

- Add a task
- View all tasks
- Mark a task as completed
- Delete a task
- Save tasks in `tasks.txt`
- Uses Java classes, objects, lists, loops, methods, and file handling

## Requirements

- Java JDK 17 or later

## How to run

1. Download or clone this repository.
2. Open a terminal in the project folder.
3. Compile the Java files:

   ```bash
   javac -d out src/main/java/com/example/taskmanager/*.java
   ```

4. Run the application:

   ```bash
   java -cp out com.example.taskmanager.Main
   ```

The application creates `tasks.txt` in the folder where you run it.

## Example

```text
=== Simple Java Task Manager ===

1. Add task
2. View all tasks
3. Mark task as completed
4. Delete task
5. Exit
Choose an option: 1
Enter task title: Learn Java
Task added successfully.
```

## Project structure

```text
simple-java-task-manager/
├── src/
│   └── main/
│       └── java/
│           └── com/example/taskmanager/
│               ├── Main.java
│               ├── Task.java
│               ├── TaskService.java
│               └── TaskRepository.java
├── .gitignore
└── README.md
```

## What I learned

- Object-oriented programming in Java
- Creating and using classes and objects
- Working with `ArrayList`
- Taking user input with `Scanner`
- Reading and writing files
- Handling basic errors and invalid input

## Future improvements

- Add due dates and task priorities
- Add search functionality
- Create a graphical user interface
- Store tasks in a database

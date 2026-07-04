# 📝 To-Do App

A simple desktop **To-Do Application** built with **Python** and **FreeSimpleGUI**. This project allows users to manage their daily tasks through an easy-to-use graphical interface while storing data in a text file for persistence.

## Features

* Add new to-do items
* Edit existing tasks
* Mark tasks as complete
* Select a task from the list to edit it
* Automatically saves tasks in a `.txt` file
* Displays the current date and time
* Error handling for invalid actions (e.g., editing or completing without selecting a task)

## Technologies Used

* Python
* FreeSimpleGUI
* File Handling
* Event-Driven Programming

## Project Structure

```text
Todo_App_Project/
│
├── main.py                 # Main GUI application
├── functions.py            # File handling functions
├── todos_storage.txt       # Stores all to-do items
└── README.md
```

## How It Works

* Enter a task in the input field and click **Add**.
* Select a task from the list to load it into the input box.
* Modify the text and click **Edit** to update the task.
* Click **Complete** to remove the selected task.
* All tasks are automatically stored in `todos_storage.txt`, so they remain available even after closing the application.

## What I Learned

This project helped me practice:

* Building desktop GUI applications with Python
* Organizing code into multiple modules
* Reading from and writing to files
* Handling GUI events
* Improving user experience through error handling

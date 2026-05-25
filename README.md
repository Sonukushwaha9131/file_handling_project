# file_handling_project
A Python-based CLI tool to perform basic CRUD (Create, Read, Update, Delete) operations on local files.
# File Handling Project

A simple Python command-line utility for performing basic File CRUD (Create, Read, Update, Delete) operations. This interactive script provides a user-friendly menu to manage files within your local directory.

## 🚀 Features

This project revolves around the primary script, `main.py`. It includes the following capabilities:

* **Directory Listing:** Automatically displays all files and folders in the current directory before executing file operations.
* **Create Files:** Prompts the user to generate a new file and write initial text into it[cite: 1]. Prevents accidental overwriting if the file already exists[cite: 1].
* **Read Files:** Opens and displays the contents of an existing file directly in the terminal[cite: 1].
* **Update Files:** Offers a sub-menu to modify existing files with three options[cite: 1]:
  1. Rename the file[cite: 1].
  2. Overwrite the file's current data[cite: 1].
  3. Append new content to the end of the file[cite: 1].
* **Delete Files:** Safely removes a specified file from the directory[cite: 1].

## 🛠️ Prerequisites

* **Python 3.x** must be installed on your system (the script utilizes the `pathlib` and `os` modules, which are included in the Python Standard Library)[cite: 1].

## 💻 How to Run

1. Clone this repository to your local machine.
2. Open your terminal or command prompt.
3. Navigate to the directory where the project is saved.
4. Execute the following command to start the program:

```bash
   python main.py

📖 Usage
Upon running main.py, you will be presented with a numbered menu[cite: 1]. Type the number corresponding to the action you want to take and press Enter:

1 - Create a file

2 - Read a file

3 - Update a file

4 - Delete a file



   

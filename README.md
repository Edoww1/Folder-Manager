# 📁 Folder Manager

A simple Python tool for automatically organizing files into folders based on their file extensions.

## 🎯 About the project

Folder Manager is a small Python project created to practice file and folder manipulation.

The program asks the user for a folder path, scans the files inside it, and automatically sorts them into dedicated folders according to their file extensions.

For example:

- `.py` → `Python_files/`
- `.png` → `PNG_files/`
- `.pdf` → `PDF_files/`
- `.jpg` → `JPG_files/`
- `.jpeg` → `JPEG_files/`
- Other file types → `Others/`

The goal of this project was to learn how to interact with the file system using Python and automate a repetitive task.

## 🛠️ Technologies

- **Python 3**
- `pathlib`
- `os`
- `shutil`

## ⚙️ Features

- 📂 Choose the folder to organize
- 🔎 Scan files inside the selected folder
- 🗂️ Detect file extensions automatically
- 📁 Create destination folders when necessary
- 🚚 Move files into their corresponding folders
- ⚡ Automate file organization

## 📚 What I learned

This project allowed me to practice:

- Working with files and directories in Python
- Using `pathlib.Path`
- Checking files and directories with `os`
- Moving files with `shutil`
- Working with file extensions
- Using loops and conditions
- Using `match/case`
- Automating repetitive tasks
- Building a simple command-line application

## 🚀 Possible improvements

Future versions could include:

- [ ] Support for more file extensions
- [ ] A configuration system for custom categories
- [ ] A preview mode before moving files
- [ ] Better error handling
- [ ] A graphical user interface
- [ ] A log of moved files

## 📦 Download

The project is available as a standalone Windows executable.

See the **Releases** section to download `FolderManager.exe`.

## 👨‍💻 Author

**Sir Edoww**

Student in Computer Science Engineering — IG2I, Centrale Lille.

This project was created as part of my personal programming practice.


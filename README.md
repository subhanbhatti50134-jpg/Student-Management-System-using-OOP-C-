# Student Management System (C++ OOP)

A beginner C++ console project that manages student records using object-oriented
programming and file handling.

## What it does

- Store student details: name, age, student ID, major, and GPA
- Model students with a `Person` base class and a `Student` subclass (inheritance,
  virtual `display()`, copy constructors, virtual destructor)
- Save all student records to a text file (`students.txt`) and load them back
- Interactive console menu to add, view, and persist students

## Who it's for

Students learning C++ fundamentals: classes, inheritance, file I/O, and console
applications.

## Features

- `Person` class: name, age, ID with getters/setters
- `Student` class: adds major and GPA, overrides `display()`
- `saveToFile()` / `loadFromFile()`: persist records to disk
- Virtual destructor and copy constructors for correct object lifecycle

## Compile and run

Prerequisites: a C++ compiler (e.g. `g++`).

```bash
# clone
git clone https://github.com/subhanbhatti50134-jpg/Student-Management-System-using-OOP-C-.git
cd "Student-Management-System-using-OOP-C-"

# compile
g++ main.cpp -o student_management

# run
./student_management
```

Windows (PowerShell):

```powershell
g++ main.cpp -o student_management.exe
.\student_management.exe
```

Records are saved to `students.txt` in the working directory.

## Notes

- This is a learning project. Data is stored in a plain text file, not a
  database, and there is no input validation beyond the basics shown.
- Compilation was not tested in this environment; the GitHub Actions workflow
  verifies it builds with `g++`.

## License

This repository does not yet carry an open-source license. See
`LICENSE_DECISION.md` for recommended options.

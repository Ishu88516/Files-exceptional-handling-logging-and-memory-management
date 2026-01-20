# 📘 Python File Handling, Exception Handling, Logging & Memory Management

## 📌 Project Overview

This project demonstrates core Python concepts related to **file operations**, **exception handling**, **logging**, and **basic memory profiling**.
It is designed for learning, practice, and interview/exam preparation.

The examples cover common real-world scenarios such as reading and writing files, handling runtime errors, logging application events, and monitoring memory usage.

---

## 🧰 Topics Covered

### 📂 File Handling

* Opening files in different modes (`r`, `w`, `a`)
* Reading files line by line
* Writing and appending data to files
* Copying contents from one file to another
* Checking if a file exists or is empty
* Using context managers (`with` statement)

### ⚠️ Exception Handling

* Handling `FileNotFoundError`
* Catching `ZeroDivisionError`
* Managing `KeyError` and `IndexError`
* Using multiple `except` blocks
* Writing robust programs with `try-except-else-finally`

### 📝 Logging

* Logging messages at different levels:

  * `INFO`
  * `WARNING`
  * `ERROR`
* Logging errors to a file
* Rotating log files after a specific size
* Logging exceptions with stack traces

### 🧠 Memory Management

* Basic memory profiling
* Tracking memory usage of functions
* Understanding memory allocation in Python

---

## 🛠️ Technologies Used

* **Python 3**
* Built-in modules:

  * `os`
  * `logging`
  * `logging.handlers`
* External module:

  * `memory_profiler`

---

## 📁 Project Structure

```
├── Files,_exceptional_handling,_logging_and_memory_management.ipynb
├── example.txt
├── error.log
├── app.log
├── numbers.txt
└── README.md
```

---

## ▶️ How to Run

1. Make sure Python 3 is installed.
2. (Optional) Install memory profiler:

   ```bash
   pip install memory-profiler
   ```
3. Open and run the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

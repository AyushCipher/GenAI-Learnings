# 🐍 Complete Python Bootcamp

A comprehensive, step-by-step master repository covering core Python programming, advanced concepts, data analysis, database integration, web development (Flask & Streamlit), and high-performance concurrency.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Repository Structure & Curriculum](#-repository-structure--curriculum)
  - [1. Python Basics](#1-python-basics)
  - [2. Control Flow](#2-control-flow)
  - [3. Data Structures](#3-data-structures)
  - [4. Functions](#4-functions)
  - [5. Modules & Packages](#5-modules--packages)
  - [6. File Handling](#6-file-handling)
  - [7. Exception Handling](#7-exception-handling)
  - [8. Object-Oriented Programming (OOP)](#8-object-oriented-programming-oop)
  - [9. Advanced Python Concepts](#9-advanced-python-concepts)
  - [10. Data Analysis with Python](#10-data-analysis-with-python)
  - [11. Working with Databases](#11-working-with-databases)
  - [12. Logging in Python](#12-logging-in-python)
  - [13. Web Development with Flask](#13-web-development-with-flask)
  - [14. Interactive Web Apps with Streamlit](#14-interactive-web-apps-with-streamlit)
  - [15. Memory Management & Profiling](#15-memory-management--profiling)
  - [16. Multithreading & Multiprocessing](#16-multithreading--multiprocessing)
- [Prerequisites & Installation](#-prerequisites--installation)
- [How to Use This Repository](#-how-to-use-this-repository)
- [License](#-license)

---

## 📖 Overview

This repository is designed as a complete roadmap for mastering Python from fundamental syntax to production-grade applications. Each module includes hands-on Jupyter Notebooks (`.ipynb`) and standalone Python scripts (`.py`) for practical learning.

---

## 📂 Repository Structure & Curriculum

### 1. Python Basics
**Folder:** `1-Python Basics/`
- **1.0-basic.ipynb**: Python syntax, indentation rules, comments, and standard output.
- **1.1-Variables.ipynb**: Variable assignment, naming conventions, dynamic typing, and memory references.
- **1.2-Datatypes.ipynb**: Built-in primitive types (integers, floats, strings, booleans) and type casting.
- **1.3-operators.ipynb**: Arithmetic, comparison, logical, assignment, identity (`is`), and membership (`in`) operators.
- **test.py**: Basic script demonstration.

### 2. Control Flow
**Folder:** `2-Control Flow/`
- **Conditionalstatements.ipynb**: `if`, `elif`, `else` constructs and nested decision structures.
- **Loops.ipynb**: `for` and `while` loops, iteration control (`break`, `continue`, `pass`), and `range()` function.

### 3. Data Structures
**Folder:** `3-Data Structures/`
- **3.1-Lists.ipynb**: List initialization, indexing, slicing, and built-in methods (`append`, `extend`, `insert`, `pop`, `remove`, `sort`, `reverse`).
- **3.1.1-ListExamples.ipynb**: Practical list exercises and list comprehension patterns.
- **3.2-Tuples.ipynb**: Immutable sequences, tuple packing/unpacking, and use cases.
- **3.3-Sets.ipynb**: Unordered unique collections, set operations (union, intersection, difference, symmetric difference).
- **3.4-Dictionaries.ipynb**: Key-value mapping, dictionary methods (`keys`, `values`, `items`, `get`, `update`), and dictionary comprehensions.

### 4. Functions
**Folder:** `4-Functions/`
- **4.1-functions.ipynb**: Function definitions (`def`), return values, default parameters, variable-length arguments (`*args`, `**kwargs`), and docstrings.
- **4.2-examplesfunctions.ipynb**: Practical problem-solving and recursion.
- **4.3-Lambda.ipynb**: Anonymous functions and short inline expressions.
- **4.4-Mapsfunction.ipynb**: Applying transformations using the `map()` higher-order function.
- **4.5-filterfunction.ipynb**: Filtering collections conditionally using the `filter()` function.

### 5. Modules & Packages
**Folder:** `5-Modules/`
- **5.1-import.ipynb**: Creating and importing custom modules, namespace handling, `from ... import ...`.
- **5.2-Standardlibrary.ipynb**: Python Standard Library exploration (`math`, `random`, `os`, `sys`, `datetime`).
- **package/**: Directory structure illustrating package creation with `__init__.py` and subpackages (`package/maths.py`, `package/subpackages/mult.py`).

### 6. File Handling
**Folder:** `6-File Handling/`
- **6.1-fileoperation.ipynb**: File modes (`r`, `w`, `a`, `rb`, `wb`), context managers (`with open()`), read/write techniques.
- **6.2-filepath.ipynb**: Path manipulation with `os.path` and working with directory structures.

### 7. Exception Handling
**Folder:** `7-Exception Handling/`
- **7.1-exception.ipynb**: Handling runtime errors with `try`, `except`, `else`, and `finally` blocks, raising custom exceptions, and built-in error types.

### 8. Object-Oriented Programming (OOP)
**Folder:** `8-Class And Objects/`
- **8.1-oops.ipynb**: Classes, objects, attributes, `__init__` constructor, instance vs. class variables.
- **8.2-inheritance.ipynb**: Single, multiple, multilevel, and hierarchical inheritance with `super()`.
- **8.3-Polymorphism.ipynb**: Method overriding and polymorphic design patterns.
- **8.4-Encapsulation.ipynb**: Access modifiers (public, protected `_`, private `__`) and getter/setter methods.
- **8.5-Abstraction.ipynb**: Abstract Base Classes (ABC) and `@abstractmethod`.
- **8.6-magicmethods.ipynb**: Special dunder methods (`__str__`, `__repr__`, `__len__`, `__getitem__`, etc.).
- **8.7-OperatorOverloading.ipynb**: Overloading mathematical and relational operators (`__add__`, `__sub__`, `__eq__`).

### 9. Advanced Python Concepts
**Folder:** `9-Advance Python Concepts/`
- **9.1-Iterators.ipynb**: Iterators vs. Iterables, `iter()`, `next()`, and implementing custom iterator protocols.
- **9.2-Generators.ipynb**: Memory-efficient stream generation using `yield` and generator expressions.
- **9.3-Decorators.ipynb**: Closures, higher-order functions, function decorators (`@decorator`), and parameterized decorators.

### 10. Data Analysis with Python
**Folder:** `10-Data Analysis With Python/`
- **10.1-numpy.ipynb**: N-dimensional array creation, slicing, broadcasting, and numerical operations.
- **10.2-pandas.ipynb**: Series, DataFrames, indexing, querying, and exploratory data analysis.
- **10.3-datamanipulation.ipynb**: Handling missing values (`NaN`), data cleaning, grouping (`groupby`), joins, and aggregations.
- **10.4-readdata.ipynb**: Ingesting and exporting datasets (CSV, Excel `.xlsx`, JSON).
- **10.5-matplotlib.ipynb**: 2D plotting (line charts, bar charts, scatter plots, histograms, subplots).
- **10.6-seaborn.ipynb**: Statistical data visualization (heatmaps, pairplots, boxplots, countplots, distribution plots).

### 11. Working with Databases
**Folder:** `11-Working With Databases/`
- **11.1-sqlite.ipynb**: Connecting to SQLite via `sqlite3`, schema definition, CRUD operations (Create, Read, Update, Delete), and querying data directly into Pandas DataFrames.

### 12. Logging in Python
**Folder:** `12-Logging In Python/`
- **12.1-logging.ipynb**: Standard logging levels (`DEBUG`, `INFO`, `WARNING`, `ERROR`, `CRITICAL`), basic configuration, and log formatting.
- **12.2-multiplelogger.ipynb**: Multi-module logging architecture, stream vs. file handlers, custom formatters, and modular logging (`logs/logger.py`).

### 13. Web Development with Flask
**Folder:** `13-Flask/`
- **flask/app.py & main.py**: Minimal Flask web applications, routes, and URL binding.
- **flask/getpost.py**: Handling HTTP `GET` and `POST` requests and form processing.
- **flask/jinja.py**: Jinja2 templating, dynamic HTML rendering, conditionals, and loops.
- **flask/api.py**: Building RESTful APIs with Flask returning JSON endpoints.
- **flask/templates/**: HTML template files (`index.html`, `about.html`, `form.html`, `result.html`, `getresult.html`).

### 14. Interactive Web Apps with Streamlit
**Folder:** `14-Streamlit/`
- **streamlit.ipynb & app.py**: Creating interactive dashboards and data applications with pure Python.
- **widgets.py**: Interactive UI components (buttons, sliders, inputs, selectboxes, checkboxes).
- **classification.py**: End-to-end Machine Learning web app with Scikit-Learn and Streamlit for model predictions.

### 15. Memory Management & Profiling
**Folder:** `15-Memory Management/`
- **memory_manage.ipynb**: Python memory model, stack vs. heap allocation, reference counting, cyclic references, garbage collection (`gc` module), and line-by-line memory profiling with `memory_profiler`.

### 16. Multithreading & Multiprocessing
**Folder:** `16-Multithreading and Multiprocessing/`
- **multi_threading.py & advance_multi_threading.py**: Concurrent execution for I/O-bound operations using `threading` and `ThreadPoolExecutor`.
- **webscrapping_multi_threading.py**: Multi-threaded concurrent web scraping example.
- **multi_processing.py & advance_multi_processing.py**: True parallel execution for CPU-bound tasks using `multiprocessing` and `ProcessPoolExecutor`.
- **factorial_multi_processing.py**: Parallelized heavy mathematical computations.

---

## 🚀 Prerequisites & Installation

### 1. Clone the Repository
```bash
git clone https://github.com/krishnaik06/Complete-Python-Bootcamp.git
cd Complete-Python-Bootcamp
```

### 2. Create and Activate a Virtual Environment
- **Windows:**
  ```powershell
  python -m venv venv
  .\venv\Scripts\activate
  ```
- **macOS / Linux:**
  ```bash
  python3 -m venv venv
  source venv/bin/activate
  ```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

---

## 💻 How to Use This Repository

### Running Jupyter Notebooks
Launch JupyterLab or Jupyter Notebook:
```bash
jupyter notebook
```
Navigate through folders `1` to `15` to run and experiment with the interactive notebooks.

### Running Python Scripts
Execute any standalone script:
```bash
python "16-Multithreading and Multiprocessing/multi_threading.py"
```

### Running the Flask App
```bash
cd "13-Flask/flask"
python app.py
```
Open your browser at `http://127.0.0.1:5000/`.

### Running Streamlit Applications
```bash
cd "14-Streamlit"
streamlit run app.py
# Or run the ML classification app:
streamlit run classification.py
```
Open your browser at `http://localhost:8501/`.

---

## 📜 License

This project is licensed under the terms of the [LICENSE](LICENSE) file included in this repository.
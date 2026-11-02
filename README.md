<h1 align="center">🐍 Python Learning Projects</h1>

<p align="center">
  <strong>A collection of beginner-friendly Python notebooks covering core programming concepts and small interactive projects.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python 3" />
  <img src="https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter notebooks" />
  <img src="https://img.shields.io/badge/Google-Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white" alt="Google Colab" />
</p>

---

## ✨ Overview

`SD_Muskan_Shukla_0058` is a learning repository containing Jupyter notebooks with Python practice exercises and small command-line projects. The notebooks demonstrate topics such as collections, loops, functions, generators, input handling, arithmetic, and simple conditional logic.

The projects run interactively: they ask for values in notebook cells and print results. They use Python's standard library and do not require a database, web server, or third-party packages.

## 📚 Notebooks

| Notebook | What it covers |
|---|---|
| [`DAY_2.ipynb`](DAY_2.ipynb) | Python practice with dictionaries, lists, tuples, sets, loops, comprehensions, type conversion, functions, return values, and Fibonacci generators. It also includes a menu-based calculator with addition, subtraction, multiplication, division, and basic input validation. |
| [`PROJECT_2.ipynb`](PROJECT_2.ipynb) | Student marks calculator: collects marks for five subjects, calculates a percentage and an approximate GPA, and assigns a letter grade to each subject. |
| [`PROJECT_DAY2_ATM.ipynb`](PROJECT_DAY2_ATM.ipynb) | A simple ATM withdrawal simulation with a PIN check, starting balance, and withdrawal amount input. |
| [`EXPENSE_TRACKER_PROJECT3.ipynb`](EXPENSE_TRACKER_PROJECT3.ipynb) | A basic expense tracker that collects food, movie, travel, and other expenses and prints a category summary and total. |

## 🧰 Concepts & Tools

| Area | Examples in the notebooks |
|---|---|
| Python fundamentals | Variables, types, conversions, arithmetic, strings |
| Collections | Dictionaries, lists, tuples, and sets |
| Control flow | `if`/`elif`/`else`, `for` and `while` loops, `break`, `continue` |
| Functions | Parameters, return values, multiple return values |
| Iteration | List/dictionary comprehensions and Fibonacci generators |
| Notebook runtime | Jupyter Notebook or Google Colab |

## 🚀 Getting Started

### Option 1: Google Colab

The notebooks include Google Colab links in their first cells. Open a notebook from the repository and select **Open in Colab**, or visit the repository in GitHub and click the Colab badge at the top of a notebook.

### Option 2: Run locally with Jupyter

Prerequisite: Python 3. Install Jupyter if it is not already available:

```bash
python -m pip install jupyter
```

Clone the repository and launch Jupyter from its directory:

```bash
git clone https://github.com/MuskanShukla30/SD_Muskan_Shukla_0058.git
cd SD_Muskan_Shukla_0058
python -m jupyter notebook
```

Open one of the `.ipynb` files in the browser, then run cells from top to bottom. The project notebooks use `input()`, so run their interactive cells in a notebook environment that supports standard input.

## 🧩 Project Details

### Student Marks Calculator

The notebook asks for a student name and marks in five subjects (Maths, COA, TAFL, OS, and DSTL). It totals the marks, calculates a percentage from a maximum of 500, estimates GPA by dividing the percentage by 9.5, and prints a subject grade using these thresholds:

| Marks | Grade |
|---:|:---:|
| 80 and above | A |
| 60–79 | B |
| 50–59 | C |
| 40–49 | D |
| Below 40 | F |

### ATM Simulation

The ATM notebook starts with a balance of ₹5,000 and requests a PIN. If the PIN matches, it asks for a withdrawal amount and prints the resulting balance. This is a basic exercise and does not persist balances between runs.

### Expense Tracker

The expense tracker requests a user ID and password before collecting four integer expense amounts: food, movies, travel, and other. If the credentials match, it displays each category and their total.

The current demo values in the notebook are:

| Field | Value |
|---|---|
| User ID | `admin` |
| Password | `1234` |

These are hard-coded examples for learning only; do not use them to protect real data.

## 📁 Repository Structure

```text
SD_Muskan_Shukla_0058/
├── DAY_2.ipynb                 # Python fundamentals and calculator exercise
├── PROJECT_2.ipynb             # Student marks and grade calculator
├── PROJECT_DAY2_ATM.ipynb      # Basic ATM withdrawal simulation
└── EXPENSE_TRACKER_PROJECT3.ipynb # Interactive expense summary
```

## ⚠️ Notes

- The ATM PIN (`1909`) and expense tracker credentials (`admin` / `1234`) are hard-coded in the notebooks for demonstration. They are not secure authentication.
- The ATM exercise does not validate that a withdrawal is positive or within the available balance.
- The notebooks are introductory examples rather than production-ready financial or grading software.
- No dependency manifest is included; the project notebooks use Python built-ins. Install Jupyter separately only if running locally.

---

<p align="center"><strong>Practice, experiment, and keep learning Python 🐍</strong></p>

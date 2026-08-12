# Python Course

A beginner-friendly, hands-on Python course. It's aimed at people writing their very first
lines of code, with a secondary focus on skills useful for data engineering (files, JSON,
APIs, logging).

The course is built as a series of Jupyter notebooks, one per chapter, each following a
theory → demo → practice structure.

## Folder structure

- **`notebooks/`** — the complete course notebooks, with all code cells filled in and
  worked solutions included. Use these to follow along or teach from.
- **`practice_notebooks/`** — the same notebooks with every code cell blanked out to
  `# Your code here`, so you can read each task and write the code yourself.
- **`solution_notebooks/`** — an exact copy of `notebooks/`, code and outputs included, to
  check your work against after attempting the practice notebooks.
- **`images/`** — diagrams referenced from the notebooks (control flow, classes,
  inheritance, data structures, etc.).

## Chapters

1. Your First Python Program
2. Core Python Basics
3. Control Flow and Logic
4. Strings and Text Processing
5. Lists, Tuples, Dictionaries, and Sets
6. Functions and Reusability
7. Classes and Inheritance
8. Modules, Packages, and Imports
9. Error Handling and Debugging
10. Logging
11. Working with Files and System Libraries
12. Working with APIs and External Data
13. Streamlit Basics

## Getting started

1. **Install Python** (3.10 or newer recommended).
2. **Create and activate a virtual environment**:
   ```
   python -m venv .venv
   .venv\Scripts\activate      # Windows
   source .venv/bin/activate   # macOS/Linux
   ```
3. **Open the course in VS Code or Jupyter**, and work through the notebooks in
   `practice_notebooks/` in order, checking your answers against `solution_notebooks/`
   as you go.
4. Some later chapters (APIs, Streamlit) call external services and expect secrets such
   as API keys in a local `.env` file, which is not committed to version control.

## How to use this course

- Start at `01_your_first_python_program.ipynb` and work through the chapters in order —
  later chapters build on earlier ones.
- Try each notebook in `practice_notebooks/` yourself before looking at the matching file
  in `solution_notebooks/`.
- Refer to `notebooks/` if you want to see the fully worked version alongside the task
  descriptions.

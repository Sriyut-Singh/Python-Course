# Python for AI/ML — Learning Notes & Practice

**Author:** Sriyut Singh

This repository is a topic-wise, lecture-wise collection of Python notebooks I wrote while learning Python as a foundation for AI/ML. It covers everything from core Python syntax to NumPy, Pandas, data visualization, and several mini-projects. It's organized here so anyone starting out with Python for AI/ML — including future-me — can follow it in order.

> These notebooks come from personal class/practice sessions and were cleaned up, reorganized, and lightly annotated for public sharing. Each notebook starts with a clear title header so it's easy to tell which topic/lecture you're in, with the original code and output preserved below it. Expect some rough edges — that's part of the learning process!

> 👋 I'm a 1st-year student learning Python as a stepping stone toward AI/ML. This repo is my running log of that journey — not a polished textbook, just real practice, real mistakes, and real progress.

## 📂 Repository Structure

Each top-level folder is a **topic**, numbered in the order you should study them, and **has its own `README.md`** describing exactly what's inside that folder, notebook by notebook. Inside each topic folder, notebooks are numbered `lec-01`, `lec-02`, ... in the order they should be worked through.

```
01-python-basics/            → syntax, data types, input/output, loops, patterns, debugging
02-data-structures/          → lists, tuples, sets, dictionaries, slicing
03-functions-and-oops/       → functions and object-oriented programming
04-modules-and-random/       → built-in modules, the calendar & random libraries
05-numpy-and-pandas/         → NumPy arrays and Pandas DataFrames
06-data-visualization/       → Matplotlib and Seaborn
07-networking/                → socket programming, client-server basics
08-gui-tkinter/               → building GUIs with Tkinter (calculators, clocks, image apps)
09-mini-projects/             → Tic-Tac-Toe, Hangman, Snake, Chess, ATM, Bank system, Voice assistant
10-practice-and-assignments/  → assorted practice notebooks and homework assignments
```

### Suggested learning path

1. **`01-python-basics`** — Start here if you're new to Python.
2. **`02-data-structures`** and **`03-functions-and-oops`** — Core building blocks.
3. **`04-modules-and-random`** — Using Python's standard library.
4. **`05-numpy-and-pandas`** and **`06-data-visualization`** — The essentials for any AI/ML workflow (array math, dataframes, plotting).
5. **`07-networking`** and **`08-gui-tkinter`** — Optional side quests; useful for understanding how Python interacts with the outside world and builds interfaces.
6. **`09-mini-projects`** — Apply everything above to small, fun projects.
7. **`10-practice-and-assignments`** — Extra practice problems and assignments to test your understanding.

## 🛠 How to Use

1. Clone the repo:
   ```bash
   git clone <your-repo-url>
   cd <repo-folder>
   ```
2. Install the common dependencies used across notebooks:
   ```bash
   pip install numpy pandas matplotlib seaborn jupyter pillow chess
   ```
3. Launch Jupyter and open any notebook:
   ```bash
   jupyter notebook
   ```
4. Follow the topic order above, or jump straight to whatever you want to learn. Every notebook opens with a title block (topic + lecture name), followed by the actual code and its output, so it's easy to scan on GitHub without running anything.

## 📝 Notes on the Content

- Notebooks are the original practice/class work, lightly cleaned up: renamed for consistency, grouped by topic, and given a short, styled title header at the top of each file so headings and code/output are easy to tell apart at a glance.
- A couple of notebooks referenced a third-party tutorial author's name/email in code comments (used as a learning reference at the time); these have been replaced with a placeholder name (`Dev Sharma`) since this repo is only meant to carry my own name.
- Some notebooks are informal "practice" or "assignment" files and may contain rough code, half-finished experiments, or comments in a casual style — kept intentionally, since this is meant to show a real learning journey, not a polished textbook.

## 📌 Topics Covered at a Glance

| Folder | Topics |
|---|---|
| `01-python-basics` | variables, data types, string formatting, input/output, if-else, loops, patterns, debugging |
| `02-data-structures` | lists, tuples, sets, dictionaries, slicing |
| `03-functions-and-oops` | functions, classes, objects, OOP concepts |
| `04-modules-and-random` | `calendar` module, `random` module |
| `05-numpy-and-pandas` | NumPy arrays, Pandas Series/DataFrame, data questions |
| `06-data-visualization` | Matplotlib plots, Seaborn plots |
| `07-networking` | sockets, client-server programs |
| `08-gui-tkinter` | Tkinter widgets, calculators, digital clock, image-based GUI |
| `09-mini-projects` | Tic-Tac-Toe, Hangman, Snake, Chess, Bank system, ATM, Voice assistant |
| `10-practice-and-assignments` | mixed practice sets and home assignments |

## 📜 License

Feel free to use these notebooks for learning purposes. If you reuse or adapt significant portions, a credit back to this repo is appreciated.

---
*Maintained by Sriyut Singh — built while learning Python for AI/ML.*

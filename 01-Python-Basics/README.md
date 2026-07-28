# 📘 01 — Python Basics

**Author:** Sriyut Singh

This is the very first stop on the journey — the core syntax and building blocks of Python. If you're a beginner (like me, a 1st-year student!), start right here before touching anything else in this repo.

## 📂 What's Inside

| Notebook | What it covers |
|---|---|
| `lec-01-python-start.ipynb` | First lines of Python — variables, `type()`, string concatenation/repetition, arithmetic, `id()`, comments, and a first look at operators: comparison, membership (`in`/`not in`), identity (`is`), assignment (`+=`), and bitwise. |
| `lec-02-data-types.ipynb` | Data types in depth — type casting (`str()`, `int()`, `complex()`, `float()`), the `random` module basics, `input()`, indentation, tokens, and mutable vs immutable objects (lists vs numbers via `id()`). |
| `lec-03-string-formatting.ipynb` | String formatting with `.format()` and f-strings, escape characters (`\n`, `\t`, `\'`), and string methods — `count`, `find`, `center`, `isalnum`, `isalpha`, `istitle`, `endswith`, `split`, `partition`, `ljust`/`rjust`. |
| `lec-04-user-input-if-else-pass.ipynb` | Taking user input, `if` / `elif` / `else` chains, nested conditions, a simple grade calculator, and the `pass` statement. |
| `lec-05-loops.ipynb` | `while` and `for` loops, `break` and `continue`, multiplication tables, prime-number check, and a first mini ATM-style program using conditionals inside loops. |
| `lec-06-star-patterns.ipynb` | Pattern printing with nested loops (triangles, pyramids), plus small math word problems (perimeter, area, tile calculations) solved using loops and arithmetic, and leap year / Armstrong number / strong number checks. |
| `lec-07-debugging.ipynb` | Using Python's built-in `pdb` debugger — setting breakpoints with `pdb.set_trace()` and stepping through code (factorial example). |
| `lec-08-program-to-software.ipynb` | A quick note on turning a `.py` script into a standalone executable using `pyinstaller`. |
| `lec-09-print-pattern-task.ipynb` | Many different ways to print the word "python" diagonally/vertically — looping over string indices, using `time.sleep()` for a typewriter effect, and printing numeric triangle patterns. |
| `lec-10-quick-math-practice.ipynb` | Tiny warm-up arithmetic operations in a fresh notebook cell. |

## 🧠 Key Concepts Practiced

- Variables, data types & type casting
- Operators: arithmetic, comparison, logical, membership, identity, bitwise, assignment
- Strings: formatting, escape sequences, built-in string methods
- Conditionals (`if`/`elif`/`else`, `pass`)
- Loops (`while`, `for`, `break`, `continue`, nested loops)
- Basic debugging with `pdb`
- Packaging a script into an executable

## ▶️ How to Run

```bash
jupyter notebook
```
Open any `.ipynb` file above — no external libraries are required for this folder beyond Python's standard library (`random`, `pdb`, `time`, `sys`).

---
*Part of the [Python for AI/ML](../README.md) learning series by Sriyut Singh.*



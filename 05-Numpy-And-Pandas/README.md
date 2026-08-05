# 📘 05 — NumPy & Pandas

**Author:** Sriyut Singh

The two libraries that make Python genuinely useful for AI/ML and data analysis: **NumPy** for fast numerical arrays, and **Pandas** for tabular data. This is one of the most important folders in the whole series.

## 📂 What's Inside

| Notebook | What it covers |
|---|---|
| `lec-01-numpy.ipynb` | Introduction to NumPy — what "numerical Python" means, creating arrays, and basic array operations. |
| `lec-02-numpy-and-pandas.ipynb` | The big combined notebook — reading CSV files with `pd.read_csv()`, DataFrame creation/inspection, NumPy array operations, and using both libraries together for data handling. |
| `lec-03-numpy-misc-practice.ipynb` | Miscellaneous NumPy practice — things like `np.diag()` and other array-generation/manipulation functions. |
| `lec-04-pandas-practice.ipynb` | Focused Pandas practice — DataFrame operations, selection, and manipulation exercises. |
| `lec-05-numpy-pandas-questions.ipynb` | A set of applied questions/exercises (e.g. cleaning messy columns like a `FlightNumber` field) to test understanding of NumPy and Pandas together. |

## 🧠 Key Concepts Practiced

- Creating and manipulating NumPy arrays
- Reading data into Pandas DataFrames (`read_csv`)
- Inspecting, cleaning, and selecting data in a DataFrame
- Combining NumPy + Pandas for real data-handling tasks

## ▶️ How to Run

```bash
pip install numpy pandas jupyter
jupyter notebook
```
> Note: `lec-02-numpy-and-pandas.ipynb` originally reads a CSV from a local path (`S:/num py files/ex1.csv`) — you'll need to point it to your own CSV file if you want to re-run that cell.

---
*Part of the [Python for AI/ML](../README.md) learning series by Sriyut Singh.*

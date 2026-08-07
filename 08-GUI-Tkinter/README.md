# 📘 08 — GUI with Tkinter

**Author:** Sriyut Singh

Building actual graphical desktop apps using Python's built-in **Tkinter** library — windows, buttons, labels, and message boxes, working up to small real apps like calculators and a digital clock.

## 📂 What's Inside

| Notebook | What it covers |
|---|---|
| `lec-01-tkinter-basics.ipynb` | Tkinter fundamentals — creating a window with `Tk()`, setting a title, adding a `Label`, and starting the event loop with `mainloop()`. |
| `lec-02-calculator-v1.ipynb` | First calculator attempt — a `calc` class using Tkinter and the `math` module. |
| `lec-03-calculator-v2.ipynb` | Improved calculator — button click handling that builds up an expression string and evaluates it. |
| `lec-04-calculator-attempt.ipynb` | Another calculator iteration, refining the layout/logic from earlier attempts. |
| `lec-05-calculator-mini-task.ipynb` | A smaller calculator-style mini task/game (an "(a+b)² " exercise) to reinforce the concepts. |
| `lec-06-tkinter-buttons.ipynb` | Working more deeply with `Button` widgets and click events. |
| `lec-07-tkinter-messagebox.ipynb` | Using `tkinter.messagebox` to show warning/info popups. |
| `lec-08-digital-clock.ipynb` | A live digital clock app using `time.strftime` and Tkinter's `ttk` styled widgets. |
| `lec-09-image-button-app.ipynb` | Combining Tkinter with `PIL` (Pillow) to load images (`ImageTk`, `Image`) and build an image-based button app with a file dialog. |

## 🧠 Key Concepts Practiced

- Creating windows, labels, and buttons with Tkinter
- Event-driven programming (`mainloop`, button click handlers)
- Message boxes and popups
- Live-updating widgets (clock)
- Loading images into a GUI with Pillow (`PIL`)

## ▶️ How to Run

```bash
pip install pillow
jupyter notebook
```
> Tkinter ships with standard Python installations on most systems (on some Linux distros you may need `sudo apt install python3-tk`). `lec-09-image-button-app.ipynb` additionally needs the `Pillow` (`PIL`) library and an image file to load.

---
*Part of the [Python for AI/ML](../README.md) learning series by Sriyut Singh.*

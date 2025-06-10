## 📘 SMA Crossover Backtest Strategy

A simple yet powerful backtest project using the **50-day and 200-day Simple Moving Average (SMA)** crossover strategy. Built in Python using real stock data (Infosys & HDFC Bank) via Yahoo Finance.

---

### 📊 Strategy Overview

* **Buy Signal**: When 50-day SMA crosses **above** 200-day SMA
* **Sell Signal**: When 50-day SMA crosses **below** 200-day SMA
* **Goal**: Compare strategy returns to market returns

---

### 🔧 Tools Used

* Python (Jupyter Notebook)
* `yfinance` – for downloading stock data
* `pandas` – for data wrangling
* `numpy` – for numerical logic
* `matplotlib` – for plotting price & performance

---

### 📈 Features

* Calculates 50-day & 200-day SMA
* Generates Buy/Sell signals
* Plots:

  * Stock price with SMA lines
  * Buy/Sell markers
  * Strategy vs Market cumulative returns
* Works with Indian stocks like **INFY.NS** and **HDFCBANK.NS**

---

### 📦 Files Included

| File                      | Description                       |
| ------------------------- | --------------------------------- |
| `Backtest Strategy in Python (Moving Average Crossover).ipynb`      | Main Jupyter Notebook             |
| `sma_strategy.pdf`        | PDF export of notebook            |
| `sma_signals_INFOSYS.png` | Price chart with Buy/Sell markers |
| `README.md`               | This file                         |

---

### 📚 How to Run

```bash
pip install yfinance pandas numpy matplotlib
```

Then run the notebook in Jupyter or VSCode:

```bash
jupyter notebook Backtest Strategy in Python (Moving Average Crossover).ipynb
```

---

### 📤 Sharing & Credit

This is a beginner-level trading strategy for learning purposes only.
Feel free to fork or modify it!

📣 *“Wrote my first Python backtest strategy using SMA crossover!”*

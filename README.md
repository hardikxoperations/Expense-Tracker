# 💸 Expense Tracker CLI 

This is a **command-line Expense Tracker** built using only **Python 3 standard libraries**. It allows you to:

* Add daily expenses with a category, date, amount, and optional description
* View recorded expenses by month and year
* Get a summary of how much you spent per category and per day

All data is stored in a local **tab-separated CSV file** named `expenses.csv`.

---

## ✅ Features

* Add and store expenses in a tabular `.csv` file
* Track expenses by month and year
* Summarize expenses category-wise and day-wise
* Text-based output (no graphs, no external libraries)

---

## 🧰 Built With

* **Python 3**

---

## 📦 Installation

1. Clone or download this repo:

```bash
git clone https://github.com/yourusername/expense-tracker-cli.git
cd expense-tracker-cli
```

2. Make sure you have **Python 3 installed**

3. Run from your terminal or command prompt

---

## 🚀 How to Use

### ➕ Add an Expense

```bash
python tracker.py add
```

You'll be asked for:

* Date (press Enter to use today's date)
* Category (choose from the list)
* Amount
* Optional description

### 📄 View Expenses for a Month

```bash
python tracker.py view --month 7 --year 2025
```

Displays all expenses in **July 2025**.

### 📊 Monthly Summary

```bash
python tracker.py summary --month 7 --year 2025
```

Gives total spent per category and per day.

---

## 📂 File Structure

```
expense-tracker-cli/
├── tracker.py         # Main script
├── expenses.csv       # Expense records (auto-created)
├── README.md          # This file
```

---

## 📌 Supported Categories

* Food
* Transport
* Entertainment
* Utilities
* Health
* Other

You can modify or expand the categories list inside `tracker.py`.

---

## 📝 CSV Format

The file `expenses.csv` uses **tab-separated values** for easy import into Excel or Google Sheets.

### Example:

```
Date	Category	Amount	Description
2025-07-09	Food	120	Dinner
2025-07-10	Transport	60	Auto to work
```

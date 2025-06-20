# 💸 Expense Sharing System in Python

A simple Python-based project to split expenses fairly among a group of friends. It calculates how much each person owes and provides a clear settlement summary using object-oriented programming.

---

## 📌 Objective

To help friends or small groups track shared expenses and calculate who owes whom, ensuring fairness and transparency.

---

## ⚙️ Technologies Used

- **Python 3**
- Core Python libraries (`input`, `print`)
- Future scope: `pandas`, `matplotlib`, `seaborn` for data analysis and visualization

---

## 🧩 How It Works

### ➕ Adding Expenses

Each time an expense is added:
- The payer’s balance increases.
- The participants’ balances decrease by an equal share.

### 🧮 Calculating Settlements

The program:
- Maintains balances for all friends.
- Classifies users as **creditors** or **debtors**.
- Matches and settles debts using a greedy approach with minimal transactions.

---

## 📋 Sample Input and Output

### 👥 Friends:
```text
Alice, Bob, Charlie


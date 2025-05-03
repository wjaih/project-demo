# project-demo
This is my first Git Repository
<br>
Author - Wajih-ul-Hassan

💸 Simple Finance Dashboard (Streamlit Project)

This is a personal finance tracking app built using **Streamlit**, **Pandas**, and **Plotly**.  
It allows you to upload your bank transactions, categorize expenses, and view them visually.

---

🔧 Features

- Upload a `.csv` file of your transactions
- Automatically or manually categorize your expenses
- Save category-keyword mappings in `categories.json`
- View summaries of expenses and payments
- Interactive pie chart visualization

---

## 📁 Sample CSV Format

Expected columns:
- `Date` (e.g., 01 Jan 2024)
- `Details` (merchant or transaction info)
- `Amount` (number or comma-separated string)
- `Debit/Credit` (either `Debit` or `Credit`)

---

🚀 How to Run Locally


# Install dependencies
pip install streamlit pandas plotly

# Run the app
streamlit run main.py

Tutorial credits:
This project was built by following the tutorial by Tech With Tim:
https://www.youtube.com/watch?v=wqBlmAWqa6A
🧠 What I Learned
This was one of my first practical Python projects, and I learned a lot:

✅ How to build interactive web apps using Streamlit

✅ Reading and cleaning real-world data with Pandas

✅ Handling user input, file uploads, and session state

✅ Saving data using JSON and building a simple memory system

✅ Visualizing financial summaries with Plotly Pie Charts

✅ Using .csv files and processing transaction data

✅ Structuring readable and user-friendly Python apps


📂 Files in This Project
finance_manager.py – The full source code of the finance dashboard

README.md – You're reading it!

categories.json – Auto-created to store user-defined category keywords

sample_bank_statement.csv – Example input to test the app















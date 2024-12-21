**Expense Tracker and Budget Planner**

**A Python-based application for managing personal finances with improved robustness through defensive programming practices.**


**Key Features**

Set a monthly budget and track real-time spending.

Add, edit, and delete expenses with details (date, category, amount).

Monitor expenses by category and receive alerts when spending exceeds 80% of the budget.

Export data to CSV and save records in JSON format.

Add and manage custom categories dynamically.


**Enhancements with Defensive Programming**

**Input Validation:**

Ensures proper date format (YYYY-MM-DD).

Validates numeric inputs for budget and expenses.

Prevents duplicate or invalid category names.


**Error Handling:**

Handles file I/O errors and invalid user actions with descriptive messages.

Prevents crashes with robust try-except blocks.


**Dynamic Updates:**

Real-time budget and expense summary updates.

Budget threshold alerts for proactive financial management.


**User Feedback:**

Confirmation dialogs and error messages for critical actions.


**Installation**

**Clone the repository:**

git clone https://github.com/yourusername/Python-Expense-Tracker.git

cd Python-Expense-Tracker


**Install dependencies:**

pip install -r requirements.txt


**Run the application:**

python main.py


**Usage**


**Set Budget:** Enter a monthly budget at startup.

**Add Expenses:** Input date, category, and amount.

**Manage Categories:** Add custom categories dynamically.

**View & Delete Expenses:** Display and manage recorded expenses.

**Export Data:** Save expenses as CSV or JSON.

**Monitor Spending:** Check budget balance and receive alerts at 80% usage.

**Defensive Programming Techniques**

**Input Validation:** Ensures clean data entry.

**Error Handling:** Graceful recovery from invalid actions.

**Data Integrity:** Prevents duplicates and maintains accurate calculations.

**User Feedback:** Clear prompts for successful and failed actions.


**Future Improvements**

Add data analytics with charts/graphs.

Support recurring expenses and multi-currency tracking.

Develop mobile and web versions for better accessibility.


**References and Resources**

**List of resources used during the project**

FyefoxxM. FYEFOXXM/Python-expense-tracker: A simple GUI-based python expense tracker. Retrieved December 21, 2024a from https://github.com/FyefoxxM/Python-Expense-Tracker

Anon. Expense manager. Retrieved December 21, 2024b from https://www.scribd.com/document/522084027/EXPENSE-MANAGER



# SmartBudgetManager
A project for managing Budget
# SmartBudget Manager

Version 1.0 ·  2026 · Author: BRINIS Mohammed Islam · Group: 04

A simple Excel workbook for tracking your monthly income and expenses in euros (€). It works out your balance by itself and shows an **OVER BUDGET** warning when you spend more than you planned.

## What it does

- Records income and expenses in one table (Date, Description, Type, Category, amount, Notes)
- Sorts expenses into 5 categories: Food, Transport, Rent, Health, Education
- Calculates total income, total expenses, the monthly balance and the remaining budget
- Shows a pie chart of your expenses by category
- Turns the Budget Status to OVER BUDGET (red-orange) when total expenses are higher than the total budget, and to WITHIN BUDGET (green) otherwise

## What you need

| Item | Requirement |
|---|---|
| Software | Microsoft Excel 2016, 2019, 2021 or Microsoft 365. LibreOffice Calc also works |
| File | `SmartBudget_Manager.xlsx` (no macros, no internet needed) |
| Skills | The basics: open a file, click a cell, type numbers and dates |

## Getting started

1. Open `SmartBudget_Manager.xlsx`. If a yellow bar appears, click **Enable Editing**.
2. In the **Categories** tab, type your monthly budget for each category in the **Monthly Budget** column.
3. In the **Transactions** tab, delete the 6 sample rows (select A4:G9 and press **Delete**, but leave the **Month** column alone).
4. Add each transaction on the next empty row: date, description, type (Income or Expense), category (for expenses), then the amount in the **Income** *or* the **Expense** column.
5. Open the **Dashboard** tab to see your totals, balance, budget status and chart.

## The three worksheets

| Worksheet | What it is for | Can I edit it? |
|---|---|---|
| Dashboard | Totals, balance, budget status and chart | No (it only contains formulas) |
| Transactions | Entering income and expenses (rows 4 to 50) | Yes, except the Month column |
| Categories | Category names and budgets | Only the Monthly Budget column |

## Good to know

- Don't type over the Dashboard or the Month column. They contain formulas and nothing is locked.
- Pick Type and Category from the drop-down lists instead of typing them.
- Put the amount in the column that matches the Type (Income column for income, Expense column for expenses).
- Save one copy per month, for example `SmartBudget_2026-10.xlsx`.

## Limitations

- Only 47 transactions (rows 4 to 50) are counted, and the totals include all of them whatever their month.
- Only the 5 categories above are tracked. The budget status compares total expenses with the total budget, not category by category.
- In some non-English versions of Excel the Month column shows "yyyy-09". The totals are not affected.

## More help

The full instructions are in `SmartBudget_User_Guide_BrinisMohammedIslam_Group_04.pdf`. Support: support@example.com (replace with your own contact).


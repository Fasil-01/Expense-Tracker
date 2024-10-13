# Expense Tracker CLI

A simple command-line-based expense tracker to help you manage your finances. It allows users to add, update, delete, and view expenses. The application also provides summaries of expenses, including monthly summaries and budget management.


## Features
Add Expenses: Users can add an expense with a description and amount.
Update Expenses: Users can update the details of an existing expense.
Delete Expenses: Users can remove an expense by specifying its ID.
View Expenses: Users can list all expenses.
Expense Summary: View the total expenses and summaries for a specific month.
Expense Categories: Categorize expenses and filter them by category.
Budget Management: Set monthly budgets and receive warnings if the budget is exceeded.
Export to CSV: Export the list of expenses to a CSV file.
## Requirements

The application runs from the command line and supports the following features:

Add an expense:
$ expense-tracker add --description "Lunch" --amount 20
Expense added successfully (ID: 1)

Update an expense:

$ expense-tracker update --id 1 --description "Lunch" --amount 25
Expense updated successfully (ID: 1)

Delete an expense:
$ expense-tracker delete --id 1
Expense deleted successfully (ID: 1)

List all expenses:
$ expense-tracker list
ID  Date       Description  Amount
1   2024-08-06  Lunch        $20
2   2024-08-06  Dinner       $10

View a summary of all expenses:
$ expense-tracker summary
Total expenses: $30

View a summary of expenses for a specific month:
$ expense-tracker summary --month 8
Total expenses for August: $20

$ expense-tracker budget --amount 50

Export expenses to a CSV file:
$ expense-tracker export 
## Usage

Commands include:

add: Add a new expense
update: Update an existing expense
delete: Delete an expense
list: List all expenses
summary: View expense summary
budget: Set budget 
export: Export expenses to a file
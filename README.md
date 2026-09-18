# SpendWise

SpendWise is a simple budgeting application that helps users calculate their total expenses and remaining balance from a monthly budget.

## JavaScript Concepts

This project demonstrates:

- Variables
- Data types
- User input
- Number conversion
- Arrays
- Functions
- Loops
- Calculations
- Conditional statements
- DOM manipulation
- Browser console output

## Variables

Variables are used to store important budgeting information.

For example:

- `budget` stores the user's monthly budget.
- `totalExpenses` stores the total amount spent.
- `remainingBalance` stores the money left after expenses.

## User Input

SpendWise uses the JavaScript `prompt()` function to collect information from the user.

The user enters:

- Monthly budget
- Food expenses
- Transport expenses
- Entertainment expenses

The `Number()` function converts the input into numbers so that calculations can be performed.

## Calculations

The application adds all expenses together to calculate the total expenses.

The remaining balance is calculated using:

remaining balance = budget - total expenses

## Functions

Functions make the code easier to organize and reuse.

The `calculateTotalExpenses()` function calculates the total amount spent.

The `calculateRemainingBalance()` function calculates how much money remains.

The `startBudget()` function collects user input, performs calculations, and displays the results.

## Files

- `index.html` — Contains the structure of the SpendWise webpage.
- `style.css` — Contains the styling and layout.
- `script.js` — Contains the JavaScript logic.
- `README.md` — Explains the project and JavaScript concepts.

## How to Run

1. Open `index.html` in a web browser.
2. Click the **Start Budget** button.
3. Enter your monthly budget.
4. Enter your food expenses.
5. Enter your transport expenses.
6. Enter your entertainment expenses.
7. View your results on the page.
8. Open the browser Developer Tools and check the Console for the labeled calculations.

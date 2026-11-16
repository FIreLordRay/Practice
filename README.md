# Expense Tracker

A simple Python program that adds up your expenses and lists them from smallest to largest.

## What it does

1. Asks how many expenses you have.
2. Asks you to enter each expense, one at a time.
3. Adds them up and shows your total.
4. Shows all of your expenses sorted from smallest to largest.

##  run it

You need Python 3 installed.

```bash
python expenses.py
```

## Example

```
How many expenses do you have?
3
Enter an expense
20
Enter an expense
5.50
Enter an expense
12
You spent $37.5
[5.5, 12.0, 20.0]
```

## How 

- `int(input(...))` turns the number of expenses into a whole number.
- A `for` loop with `range()` asks for each expense.
- `float()` allows amounts with cents, like `10.50`.
- `append()` adds each expense to the `expenses` list.
- `sum()` adds up the list.
- `sort(reverse=False)` puts the expenses in order from smallest to largest.

## Concepts

- User input
- Lists
- `for` loops and `range()`
- Type conversion (`int` and `float`)
- Built-in functions (`sum`, `sort`, `print`)

## Ideas

- Show the total with two decimal places, for example `$37.50`.
- Handle input that isn't a number without crashing.
- Add a name or category for each expense.

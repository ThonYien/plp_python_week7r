# PLP Python Week 7: Python Lists

## Assignment Overview

This assignment demonstrates how to work with Python lists using indexing, adding and removing items, loops, conditions, and the `len()` function.

## Project Files

* **`list_warmup.py`** — Creates a list of fruits and demonstrates indexing, `.append()`, `.remove()`, and `len()`.
* **`shopping_list.py`** — Creates an interactive shopping list manager that allows users to add, remove, and display items or quit the program.
* **`list_report.py`** — Displays a numbered list of items, counts names with more than four letters, and finds the longest item name using a loop.
* **`screenshots/`** — Contains screenshots showing the output of each Python program.

## Why Is It Safer to Check `in` Before Calling `.remove()`?

Checking whether an item exists in a list before using `.remove()` makes the program safer. If the item is not in the list, `.remove()` raises a `ValueError`, which can stop the program unexpectedly. Using the `in` operator helps us check whether the item exists and display a helpful message if it does no

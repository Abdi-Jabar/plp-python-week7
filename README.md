# Shopping List Manager

This project is a Python shopping list manager built for the PLP Week 7 assignment.

## Files

* `list_warmup.py` - Demonstrates list indexing, `.append()`, `.remove()`, and `len()`.
* `shopping_list.py` - Provides an interactive shopping list manager for adding, removing, and showing items.
* `list_report.py` - Prints a numbered shopping list, counts items with more than 4 letters, and finds the longest item name.
* `screenshots/` - Contains screenshots showing each program running.

## Why is it safer to check `in` before calling `.remove()`?

Checking `in` before calling `.remove()` makes the program safer because `.remove()` causes an error if the item does not exist in the list. Using `in` first allows the program to handle a missing item without crashing.

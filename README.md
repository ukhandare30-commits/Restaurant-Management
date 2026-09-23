# Umesh Restaurant Management System

## Overview

This is a first year CSE Python console project for Umesh Restaurant.

Small restaurants often keep menu and bills on paper. This program lets the owner change the menu in text files and lets the customer place an order and get a bill with 5% GST.

The project uses functions, lists, file handling and input checks taught in the course.

## Features

- Owner login with password `admin123`
- Owner can add, modify, delete and view menu items (CRUD)
- Separate menus: Starters, Main Course, Desserts, Drinks, Breads
- Customer can order items, change quantity and remove items
- Bill with subtotal, GST 5% and grand total
- Menu data saved in text files

## Technologies / tools used

- Python 3
- Text files for storage (`|` separated values)
- Git and GitHub

No extra libraries are required.

## Steps to install and run

1. Install Python 3.
2. Download or clone this repository.
3. Open a terminal in the project folder.
4. If menu files are missing, create them:

```
python Database.py
```

5. Start the program:

```
python main.py
```

Use `python3` if `python` does not work.

6. Main menu:
   - `1` Owner (password: `admin123`)
   - `2` Customer
   - `3` Exit

## Instructions for testing

1. Run `python Database.py` then `python main.py`.
2. Owner test: choose 1, enter `admin123`, view a menu, add one dish, modify it, delete it.
3. Wrong password test: choose 1 and type any other word. Program should say wrong password.
4. Customer test: choose 2, open Starters, order 1 item with quantity 2, view order, confirm order.
5. Check that the bill shows subtotal, GST 5% and grand total.

## Screenshots

Add terminal screenshots here after you run the program (main menu, owner menu, customer bill).

## Files

- `main.py` - main program
- `Database.py` - creates starting menu files
- `starters.txt`, `main_course.txt`, `desserts.txt`, `drinks.txt`, `breads.txt`
- `statement.md` - problem statement
- `README.md` - this file

## Author

Umesh Vijay Khandare  
CSE Core, First year, VIT Bhopal

# Project Statement

## Problem statement

Umesh Restaurant needs a simple computer program to keep the menu and to make customer bills.

Doing this on paper is slow and it is easy to make a mistake in price or GST. The owner should be able to add, change or remove dishes. The customer should be able to see the menu, build an order and get a printed bill.

This project solves that using a Python console program and text files.

## Scope of the project

In scope:

- Owner password to open the owner menu
- Add, modify, delete and view dishes in five categories
- Customer order, edit order, remove item
- Bill with 5% GST
- Store menu in text files

Out of scope:

- Graphical interface
- Online payment
- Multiple restaurants
- Database server
- Saving old bills to a file

## Target users

- Restaurant owner (password `admin123`)
- Customer placing an order at the counter

## High-level features

1. Owner module - password, then CRUD on menu files
2. Customer module - browse menu and manage current order
3. Billing module - subtotal, GST 5%, grand total

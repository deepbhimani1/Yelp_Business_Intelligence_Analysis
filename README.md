# Yelp Business Intelligence Analysis

## Overview
This project is a Python-based business intelligence application built on top of a Yelp-style database. It allows users to explore businesses and users through structured filters, view results in a tabular format, and perform basic interactions such as writing reviews or adding friends.

The goal of this project is to demonstrate how **relational data**, **user-driven filters**, and **simple analytics logic** can be combined into an interactive application.

---

## Features Covered

### Business Search
- Search businesses by:
  - Business name
  - City
  - Star rating (minimum or maximum)
- Filters are optional and case-insensitive
- Results displayed in a scrollable table
- Ability to write a review for a selected business

### User Search
- Search users by:
  - Name
  - Funny, cool, or useful status
- Filters are optional and case-insensitive
- Results displayed in a scrollable table
- Ability to add another user as a friend

### User Interaction
- Login validation using database user IDs
- Clear success and error messaging
- Navigation between pages using a GUI interface

---

## Tools & Technologies
- **Python**
- **SQL (relational database queries)**
- **Tkinter** – Graphical user interface
- **pymssql** – Database connectivity

---

## Application Structure
- Login page with user validation
- Main menu for navigation
- Business search interface
- User search interface
- Review and friend interaction flows

---

## Files in This Repository
- `main.py` – Application logic and GUI implementation  
- `ReadMe.txt` – Original project instructions and usage notes  

---

## Purpose
This project demonstrates how business data can be queried, filtered, and presented in an interactive interface using Python and SQL, simulating common workflows found in **business intelligence and data-driven applications**.

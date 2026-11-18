# Departmental Store Management System

## Overview

A console-based program written in C++ that runs a small departmental store. It keeps track of products and customers, handles checkout with a shopping cart and printed receipts, and produces inventory and sales reports.

## Features

- View all products, or view them sorted by price
- Add new products and restock existing ones
- Low stock warnings and a low stock report
- Register customers and view the customer list
- Checkout with a cart, stock checking, and cash or card payment
- 5% bulk discount when buying 10 or more of one product
- 7% sales tax and printed receipts
- Loyalty points (1 point per dollar spent)
- Sales report with totals and averages
- Input validation so bad entries do not crash the program

## Technologies Used

- C++ (C++11 or later)
- C++ standard library only (`iostream`, `string`, `iomanip`)
- Concepts used: classes and objects, arrays, pointers, functions, and bubble sort

## Setup Instructions

1. Install a C++ compiler such as g++ or Visual Studio.
2. Download or clone this repository.
3. Open a terminal in the project folder.
4. Compile the program:

   ```
   g++ -std=c++11 Department_Store_Mangement.cpp -o store
   ```

5. Run the program:

   ```
   ./store
   ```

   On Windows, run `store.exe` instead.
6. Follow the on-screen menu. Sample product IDs are 101 to 112, and sample customer IDs are 1 to 3.

## What I Learned

- How to organize a program with classes, keeping data private and using getters and methods to work with it
- How to store collections of objects in arrays and track how many slots are in use
- How pointers work, including returning the address of an object, using `->`, and checking for `nullptr` when something is not found
- How to validate user input with loops so the program keeps asking until it gets a valid answer
- How to break a large program into small, reusable functions
- How to implement a sorting algorithm (bubble sort) by hand
- How to format console output so tables and receipts line up
- How to plan a program with flow charts before and while writing the code
- The limits of this design, such as fixed array sizes and data that is lost when the program closes, and how those could be improved

## License
This project is for educational purposes

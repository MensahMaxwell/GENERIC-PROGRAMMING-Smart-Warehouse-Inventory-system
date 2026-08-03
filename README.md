# Generic Warehouse Inventory System

A Python application developed as part of the EL 162 / 234 Object-Oriented Programming course (Week 9 Lab Activity). 

This project demonstrates Generic Programming in Python using the typing module (TypeVar and Generic), allowing a single class to store and manage items of different data types while maintaining type safety and code reusability.

---

## Project Overview

Logistics and warehouse management systems deal with diverse product data—such as string product names, integer stock counts, float prices, and lists of serial numbers. 

Rather than creating separate storage classes for every product category, this system uses a single generic class Inventory[T]. The implementation allows dynamic storage, retrieval, and type display for multiple items while keeping the codebase DRY (Don't Repeat Yourself).

---

## Key Features

- Generic Class (Inventory[T]): Built using Python's typing.Generic and TypeVar to handle any specific data type dynamically.
- Multiple Item Storage: Extended list-based internal storage (self.items) to hold multiple values of the generic type T.
- Type Inspection: Includes a display_items() method that outputs both the runtime data type (type(item).__name__) and the value of each stored record.
- Type Safety: Works cleanly with static type checkers while avoiding redundant code duplication across integer, float, string, and list data types.

---

## How to Run

1. Make sure Python 3.8+ is installed on your machine.
2. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/GENERIC-PROGRAMMING-Smart-Warehouse-Inventory-System.git](https://github.com/YOUR_USERNAME/GENERIC-PROGRAMMING-Smart-Warehouse-Inventory-System.git)
## Author
Maxwell Mensah
FOE.41.006.110.25
EL 162

# WeCare-Wholesale-Management-System
A Python-based product management system built for a cosmetics and skincare shop called WeCare, . It reads product data from a text file,   applies pricing logic automatically, and generates invoices for both   suppliers and customers.

## Features
- Display product catalog with automatic selling price (200% markup on cost price)
- Restock products from suppliers, with optional price updates
- Sell products to customers with an automatic "Buy 3, Get 1 Free" promotion
- Add new products to the inventory
- Auto-generate supplier restock invoices (with 13% VAT) as text files
- Auto-generate customer purchase invoices as text files
- Persistent storage using file I/O (`product.txt`)
- Input validation and error handling throughout (invalid IDs, negative quantities, non-numeric input, missing files)

## Techs Used
- Language: Python
- IDE: IDLE
- Design tools: Draw.io (flowcharts), Microsoft Word (documentation)

## Core concepts 
- File handling
- Data structures (lists & dictionaries)
- String manipulation
- Loops
- Functions
- Exception handling

# 🗓️ January 1st Day Calculator in Java

This simple Java program calculates the **day of the week** for **1st January** of any given year using basic math and leap year logic.

## 💡 How It Works

1. Takes an input year from the user.
2. Calculates:
   - Total normal days till the previous year.
   - Total leap days using the formula:
     ```
     leap years = (year - 1)/4 - (year - 1)/100 + (year - 1)/400
     ```
3. Adds total days and takes modulo 7 to find the weekday index.
4. Uses a `switch` statement to print the actual day name (Monday, Tuesday, etc.).

## 📌 Example

Input:
Enter the year: 2025

Output:
Day on 1 January 2025 : Wednesday

## 🛠️ Technologies Used

- Java
- Scanner for input
- Basic arithmetic and control structures (`switch`, `if`, etc.)

## 🚀 Getting Started

1. Clone the repository or copy the code.
2. Compile and run using any Java IDE or terminal:
   ```bash
   javac January1.java
   java January1

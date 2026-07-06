# Payroll Management System

A simple Python console application that calculates an employee's final salary based on performance bonuses and tax deductions.

## Features

- Employee information input
- Performance-based bonus calculation
- Tax calculation based on gross salary
- Net salary calculation
- Input validation
- Clean console output

## Bonus Policy

| Performance Rating | Bonus |
|--------------------|-------|
| 5                  | 20% of base salary |
| 3 - 4              | 10% of base salary |
| 1 - 2              | No bonus |

## Tax Policy

| Gross Salary | Tax |
|--------------|-----|
| Above 7000 EGP | 15% |
| 3000 - 7000 EGP | 10% |
| Below 3000 EGP | No tax |

## Project Structure

```
Payroll_System.py
README.md
```

## How It Works

1. Enter employee name.
2. Enter department.
3. Enter base salary.
4. Enter performance rating (1–5).
5. The program calculates:
   - Performance bonus
   - Gross salary
   - Tax deduction
   - Net salary
6. Displays the payroll summary.

## Example

```
Please Enter your name : Tariq
Please Enter Your Department : IT
Please Enter your salary : 5000
Please Enter your rating (1-5) : 5

=========================
Payroll System for: Tariq
=========================
=>Department: IT
=>Base Salary: 5000.00 EGP
=>Earned Bonus: 1000.00 EGP
=>Tax Deduction: 600.00 EGP
=========================
Net Payable Cash: 5400.00 EGP
Thanks For Using Eng Tariq
```

## Technologies Used

- Python 3
- Functions
- Conditional Statements
- User Input
- Formatted Output

## Future Improvements

- Store employee records in a database
- Export payroll reports
- Add a graphical user interface (GUI)
- Support multiple employees
- Read employee data from CSV or Excel files

---

Developed by **Tariq Alaa**

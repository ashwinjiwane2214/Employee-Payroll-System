# Payroll System

This Java program simulates a simple payroll system to manage full-time and part-time employees. It allows adding employees, removing employees, and displaying employee details.

## Features

- **Employee Class Hierarchy**: Defines an abstract `Employee` class with subclasses `FullTimeEmployee` and `PartTimeEmployee`.
- **Polymorphism**: Utilizes polymorphism with the `calculateSalary()` method overridden in subclasses.
- **Payroll System Class**: Manages a list of employees, allowing addition, removal, and display of employee details.
- **Main Class**: Demonstrates the functionality of the payroll system.

## How to Use

1. **Compile**: Compile the `Main.java` file using a Java compiler.
    ```bash
    javac Main.java
    ```

2. **Run**: Run the compiled program.
    ```bash
    java Main
    ```

3. **Interact**: Follow the on-screen prompts to add, remove, and display employee details.

## Classes

- **Employee**: Abstract class representing an employee with name, ID, and salary calculation method.
- **FullTimeEmployee**: Subclass of `Employee` representing a full-time employee with a monthly salary.
- **PartTimeEmployee**: Subclass of `Employee` representing a part-time employee with hours worked and hourly rate.
- **PayrollSystem**: Manages a list of employees and provides methods to add, remove, and display employee details.
- **Main**: Main class to demonstrate the functionality of the payroll system.

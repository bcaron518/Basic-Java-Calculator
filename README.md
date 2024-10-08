# Basic Calculator Application

This is a simple **Calculator Application** built using **Java Swing**. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

- **Addition** (`+`)
- **Subtraction** (`-`)
- **Multiplication** (`*`)
- **Division** (`/`)
- **Clear** (`C`) – Clears the display.
- **Delete** (`Del`) – Deletes the last entered digit.
- **Decimal Point** (`.`) – Allows decimal number input.
- **Equal** (`=`) – Performs the selected arithmetic operation and displays the result.

## Requirements

- **Java Development Kit (JDK)**: Version 8 or higher
- **IDE (Optional)**: Any Java-compatible IDE (like IntelliJ IDEA, Eclipse, NetBeans, etc.)

## How to Run

### Using an IDE

1. Clone or download this repository.
2. Open the project in your preferred Java IDE.
3. Run the `Calculator` class.

### Using Command Line

1. Make sure you have JDK installed on your machine. To check, run:

    ```bash
    java -version
    ```

2. Navigate to the directory where the Java source file (`Calculator.java`) is located.
3. Compile the Java file:

    ```bash
    javac Calculator.java
    ```

4. Run the compiled class:

    ```bash
    java Calculator
    ```

## Code Explanation

The calculator is built using Java Swing, with the following key components:

- **JFrame**: The main window where all the components are displayed.
- **JTextField**: Displays the input numbers and the results.
- **JButton**: Buttons for the numbers (`0-9`) and operations (`+`, `-`, `*`, `/`, `=`, `Del`, `C`, and `.`).
- **JPanel**: A grid layout panel used to organize the buttons.

### Key Functions:

1. **Number Buttons**: These append the number to the display.
2. **Operation Buttons**: These store the first number and the operator. After entering the second number and pressing the `=` button, the result is calculated and displayed.
3. **Clear Button**: Resets the calculator display.
4. **Delete Button**: Deletes the last digit entered.

## Example

### User Flow:

1. Input the first number.
2. Select an operation (`+`, `-`, `*`, `/`).
3. Input the second number.
4. Press the `=` button to see the result.

### Example Calculation:


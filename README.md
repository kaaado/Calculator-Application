# Calculator Application

This is a simple calculator application built using Java Swing. The application can perform basic arithmetic operations such as addition, subtraction, multiplication, and division. Additionally, it includes a functionality to invert the digits of the input number.

## Features

- **Addition**: Adds two numbers.
- **Subtraction**: Subtracts the second number from the first number.
- **Multiplication**: Multiplies two numbers.
- **Division**: Divides the first number by the second number.
- **Inverse**: Inverts the digits of the input number.
- **Clear (C)**: Removes the last digit from the input.
- **All Clear (AC)**: Clears the input field.

## Usage

### Buttons

- **0-9**: Digits to enter the number.
- **.**: Decimal point.
- **+**: Addition operation.
- **-**: Subtraction operation.
- **x**: Multiplication operation.
- **÷**: Division operation.
- **=**: Compute the result of the entered expression.
- **inv**: Invert the digits of the input number.
- **C**: Clear the last digit.
- **AC**: Clear the input field.

### Example

1. To perform addition, enter the first number, press `+`, enter the second number, and press `=` to see the result.
2. To perform subtraction, enter the first number, press `-`, enter the second number, and press `=` to see the result.
3. To multiply, enter the first number, press `x`, enter the second number, and press `=` to see the result.
4. To divide, enter the first number, press `÷`, enter the second number, and press `=` to see the result.
5. To invert digits, enter a number and press `inv` to see the digits inverted.

## Code Structure

The main file is `calculs.java` which contains the following key methods:

- **`BacActionPerformed`**: Clears the input field.
- **`BmActionPerformed`**: Sets the operation to subtraction.
- **`BdActionPerformed`**: Sets the operation to division.
- **`BxActionPerformed`**: Sets the operation to multiplication.
- **`BpActionPerformed`**: Sets the operation to addition.
- **`BeActionPerformed`**: Computes the result based on the selected operation.
- **`binvActionPerformed`**: Inverts the digits of the input number.
- **`CActionPerformed`**: Clears the last digit from the input field.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed on your machine.

### Running the Application

1. Clone the repository to your local machine.
2. Open the project in your preferred Java IDE.
3. Run the `calculs.java` file.

```bash
javac calculs.java
java calculs

# Python Calculator Project

A simple Python calculator application with basic arithmetic operations.

## Features

- **Addition**: Add two numbers
- **Subtraction**: Subtract two numbers
- **Multiplication**: Multiply two numbers
- **Division**: Divide two numbers (with zero division handling)

## Files

- `calculator.py` - Main calculator module with arithmetic functions
- `test_calculator.py` - Unit tests for the calculator module

## Running the Calculator

```bash
python calculator.py
```

## Running Tests

```bash
python -m unittest test_calculator.py
```

Or run all tests:

```bash
python -m unittest discover -s . -p "test_*.py"
```

## CI/CD

This project uses GitHub Actions for continuous integration. The CI workflow automatically:
- Installs dependencies
- Lints code with flake8
- Runs unit tests

The workflow triggers on push to `develop` and `feature/**` branches.

## Requirements

- Python 3.10+


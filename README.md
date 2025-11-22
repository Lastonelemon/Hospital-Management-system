# Password Strength Checker & Generator

A Python-based application to check password strength and generate secure passwords.

## Features

- **Password Strength Checker**: Analyzes passwords and provides a strength score (0-6)
- **Password Generator**: Creates strong passwords with customizable length
- **Visual Feedback**: Displays strength with progress bars
- **Detailed Suggestions**: Provides tips to improve weak passwords

## Requirements

- Python 3.x
- No external libraries required (uses built-in modules)

## Installation

1. Download the project files
2. Ensure Python 3.x is installed on your system
3. No additional installation needed

## How to Run

```bash
python password_checker.py
```

## Usage

### Menu Options

1. **Check Password Strength**
   - Enter any password to analyze
   - Get a strength score and improvement suggestions
   - See visual representation of password strength

2. **Generate Strong Password**
   - Specify desired password length (default: 12 characters)
   - Automatically creates a strong password
   - Includes uppercase, lowercase, numbers, and special characters

3. **Exit**
   - Close the application

## Password Strength Criteria

The checker evaluates passwords based on:

- **Length** (minimum 8 characters) - 2 points
- **Uppercase letters** - 1 point
- **Lowercase letters** - 1 point
- **Numbers** - 1 point
- **Special characters** (!@#$%) - 1 point

### Strength Levels

- **0-2 points**: WEAK
- **3-4 points**: MEDIUM
- **5-6 points**: STRONG

## Project Structure

```
password-checker/
│
├── password_checker.py    # Main application file
└── README.md             # Project documentation
```

## Python Concepts Used

- Functions
- String manipulation
- Loops (for, while)
- Conditionals (if-elif-else)
- Built-in modules (string)
- User input/output
- Lists and iteration

## Future Enhancements

- Add password history storage
- Implement entropy calculation
- Add common password dictionary check
- Create GUI interface


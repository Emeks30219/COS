# COS - Simple Python Calculator

A simple Python project that performs basic arithmetic operations, available as a Streamlit web app.

## Features
- Addition, Subtraction, Multiplication, Division
- Division by zero error handling
- Clean web interface powered by Streamlit

## How to Run

**Step 1** - Install Streamlit:
pip install streamlit
**Step 2** - Run the app:
streamlit run calculator.py
**Step 3** - Your browser will automatically open the calculator at:
http://localhost:8501
## Core Functions

```python
def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        return None
    return a / b
The Streamlit version uses the same functions as a terminal version but changes how the user interacts with the app.

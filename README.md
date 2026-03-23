# COS
Simple python calculator built using streamlit
A simple python project that performs basic arithmetic operations available in  a streamlit web app version 
  Running the streamlit web app version
 Step 1
     pip install streamlit
  Step 2
     streamlit run calculator.py
  Step 3
      Your browser will automatically open the calculator at
      Local URL: http://localhost:8501
The calculator is base on four simple functions
def add(a,b):
    return a+b

def subtract(a,b):
    return a-b

def multiply(a,b):
    return a*b

def divide(a,b):
    if b==0:
        return None
    return a/b
    The streamlit version uses the exact same functions as a terminal version but changes how the user interacts with the app.
     
     

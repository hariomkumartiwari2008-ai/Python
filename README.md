# Python

Basic Syntax
Python id="py1"
Copy code
# Hello World Program
print("Hello, World!")
🔤 Variables & Data Types
Python id="py2"
Copy code
x = 10          # Integer
y = 3.14        # Float
name = "Hariom" # String
is_valid = True # Boolean
Built-in Data Types
Numeric: int, float, complex
Sequence: list, tuple, string
Mapping: dict
Set Types: set
🔄 Control Structures
Conditional Statements
Python id="py3"
Copy code
x = 5

if x > 0:
    print("Positive")
else:
    print("Negative")
Loops
Python id="py4"
Copy code
for i in range(5):
    print(i)
    
🧱 Functions
Python id="py5"
Copy code
def add(a, b):
    return a + b

print(add(2, 3))
🧠 Object-Oriented Programming
Python id="py6"
Copy code
class Student:
    def __init__(self, name):
        self.name = name

    def display(self):
        print(self.name)

s = Student("Hariom")
s.display()
📦 Popular Libraries
NumPy → Numerical computing
Pandas → Data analysis
Matplotlib → Data visualization
Scikit-learn → Machine learning
Flask / Django → Web frameworks

⚙️ Advantages
Easy to learn and use
Versatile and powerful
Large ecosystem
Fast development speed
⚠️ Limitations
Slower than compiled languages
High memory consumption
Not ideal for mobile apps
🧪 Example Project
Python id="py7"
Copy code
# Simple Calculator

def calculator():
    a = int(input("Enter first number: "))
    b = int(input("Enter second number: "))
    
    print("Sum:", a + b)
    print("Difference:", a - b)
    print("Product:", a * b)

calculator()

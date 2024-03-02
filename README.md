# calculator
x = float(input("First number: "))  
y = float(input("Second number: "))  

def add(x, y):
    return x + y

def sub(x, y):
    return x - y

def mul(x, y):
    return x * y

def div(x, y):
    if y != 0:  
        return x / y
    else:
        return "Cannot divide by zero"

print("Select the arithmetic operation: ")
print("1. Add ")
print("2. Subtract ")
print("3. Multiply ")
print("4. Divide  ")
operation = input("Your choice: ")

if operation == "1":  
    print(add(x, y))
elif operation == "2":  
    print(sub(x, y))
elif operation == "3":  
    print(mul(x, y))
elif operation == "4": 
    print(div(x, y))
else:
    print("Invalid operation")

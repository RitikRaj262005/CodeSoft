def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "Error: Division by zero"
    return x / y

print("Simple Calculator")
print("----------------")
print("Operations:")
print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")

while True:
    # Get operation choice
    choice = input("Enter operation number (1-4), or 'q' to quit: ")
    
    if choice == 'q':
        print("Thank you for using the calculator. Goodbye!")
        break
    
    if choice not in ('1', '2', '3', '4'):
        print("Invalid input. Please try again.")
        continue
    
    # Get number inputs
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))
    
    if choice == '1':
        print(f"Result: {add(num1, num2)}")
    elif choice == '2':
        print(f"Result: {subtract(num1, num2)}")
    elif choice == '3':
        print(f"Result: {multiply(num1, num2)}")
    elif choice == '4':
        print(f"Result: {divide(num1, num2)}")
    
    print()  # Print a blank line for readability
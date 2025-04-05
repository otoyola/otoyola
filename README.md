def calculate(num1, num2, operation):
    if operation == 'add':
        return num1 + num2

num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
operation = input("Enter the operation (add, subtract, multiply, divide): ").lower()

result = calculate(num1, num2, operation)
print(f"The result is: {result}")

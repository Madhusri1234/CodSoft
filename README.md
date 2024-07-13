# CodSoft

def add(x, y):
  return x + y

def sub(x, y):
  return x - y

def mul(x, y):
  return x * y

def div(x, y):
  if y == 0:
    return "Error: Division by zero!"
  return x / y


num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))


operation = input("Enter the operation (+, -, *, /): ")


if operation == "+":
  result = add(num1, num2)
elif operation == "-":
  result = sub(num1, num2)
elif operation == "*":
  result = mul(num1, num2)
elif operation == "/":
  result = div(num1, num2)
else:
  result = "Error: Invalid operation!"

print("Result:", result)


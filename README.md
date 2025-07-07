# README.
#calculator vol.1
number1 = int(input("Give me a number: "))
number2 = int(input("Give me a second number: "))
operation = input("Choose operation (+, -, , /): ")

if operation == "+":
    result = number1 + number2
elif operation == "-":
    result = number1 - number2
elif operation == "":
    result = number1 * number2
elif operation == "/":
    if number2 != 0:
        result = number1 / number2
    else:
        result = "Cannot divide by zero"
else:
    result = "Invalid operation"

print("Result:", result)

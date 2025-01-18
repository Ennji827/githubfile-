def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a/ b):
    try:
        return a / b
    except ZeroDivisionError:
        return "Error: Division by zero is allowed."

def calculator():
    print("Welcome to the simple calculator!")
    print("Available operations:+, -, *, /")
    print("Type `exit` to quit the program.")

    While True:
          operation = input("\nEnter anoperation (+, -, *, /): ").strip()
          if operation.lower() == `exit`:
             print("Goodbye!")
             break

          if operation not in [`+`, `-`, `*`, `/`"]:
             print(Invalid operation. please try again.")
             continue

         try:
            num1 = float(input("Enter the first number: "))
            num2 = float(input(Enter the second number: "))
        except valueError:
            print(Invalid input. please enter numeric values.")
            continue

        if operation == `+`:
           print(f"Result: {add(num1, num2)}")
        elif operation == `-`:
           print(f"Result: {subtract(num1, num2)}")
        elif operation == `*`:
           print(f"Result;{multiply{num1, num2))")
        elif operation == `/`:
           print(f"Result: {divide(num1, num2))")

# run caculator
calculator

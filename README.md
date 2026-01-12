# hello
my first repository
this a python maths calculator
print("Simple Python Calculator")
print("Choose operation:")
print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")

choice = input("Enter choice (1/2/3/4): ")

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

if choice == "1":
    print("Result:", num1 + num2)

elif choice == "2":
    print("Result:", num1 - num2)

elif choice == "3":
    print("Result:", num1 * num2)

elif choice == "4":
    if num2 != 0:
        print("Result:", num1 / num2)
    else:
        print("Error: Division by zero")

else:
    print("Invalid choice")
Simple Python Calculator
Choose operation:
1. Add
2. Subtract
3. Multiply
4. Divide
Enter choice (1/2/3/4): 2
Enter first number: 16
Enter second number: 20
Result: -4.0

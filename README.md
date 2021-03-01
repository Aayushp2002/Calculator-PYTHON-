# Calculator-PYTHON-
# Simple calculator that can do basic math operation 


print("Welcome to my calculator!")
number1=float(input("Enter the number: "))
operation=input("Enter the operation(+,-,*,/): ")
number2=float(input("Enetr another number: "))

if operation=="+":
    print(number1+number2)
elif operation=="-":
    print(number1-number2)
elif operation=="*":
    print(number1*number2)
elif operation=="/":
    print(number1/number2)
else:
    print("Invalid operation")











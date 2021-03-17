# Faulty-calculator
Faulty calculator for (45*3=555, 56+9=77, 56/6=4)

operators =input("Enter a operators +, -, *, / \n")
num1=int(input("Enter 1st number\n"))
num2=int(input("Enter 2nd number\n"))

if operators=="+":
    sum = num1 + num2
    if sum==56+9:
        print("sum is 77")
    else:
        print("sum is ",sum)
elif operators=="-":
    minus = num1 - num2
    print("minus is ",minus)
elif operators=="*":
    multiply= num1 * num2
    if multiply==45*3:
        print("multiply is 555")
    else:
        print("multiply is ",multiply)
elif operators=="/":
    division =num1 / num2
    if division==56/6:
        print("division is 4")
    else:
        print("division is ",division)

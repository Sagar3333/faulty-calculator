# faulty-calculator
# Faulty Calculator

a = int(input("Enter trhe input "))
b = int(input("Enter 2 no. : "))
x = input("For Add enter + For Sub enter -  For Mul enter *  For Div enter /  \nEnter which operator you want to use :  ")

if x == '+':
    if a == 56 and b == 9:
        print("77")
    else:
        print(a+b)
        
elif x == '-':
    print(a-b)
elif x == '*':
    if a == 45 and b == 3:
        print("555")
    else:
        print(a*b)
elif x == '/':
    if a == 56 and b == 6:
        print("4")
    else:
        print(a/b)
else:
    print("Invalid Input!")

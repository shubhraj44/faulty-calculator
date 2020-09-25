# faulty-calculator
"""design a faulty calculators
"""
print("welcome to calculator devolped by shubham singh")
print("enter your first number")
n1=int(input())
print("enter your second number")
n2=int(input())
print('so what do you want? '+'+,-,*,/')
n3=input()

if n3=='+':
    if n1==56:
        print("56+9=77")
    else:
        print("result",int(n1)+int(n2))
if n3=='*':
    if n1==45:
        print("45*3=555")
    else:
        print("result",int(n1)*int(n2))
if n3=='/':
    if n1==56:
        print("56/9=4")
    else:
        print("result",int(n2)/int(n2))
if n3=='-':
    print("result",int(n1)-int(n2))
    """hope u likr the program
    """

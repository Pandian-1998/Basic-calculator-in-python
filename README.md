# basic-calculator-in-python
select=input("select your option:\n"
             "0.Addition\n"
             "1.Subtraction\n"
             "2.Multiplication\n"
             "3.Division\n")
n1=float(input("enter the no:"))
n2=float(input("enter the no:"))
if(select=='0'):
    print("Addition",n1 + n2)
elif(select=='1'):
    print("Subtraction",n1 - n2)
elif select == '2':
    print("Multiply",n1 * n2)
elif select == '3':
    print("Division",n1 / n2)
else:
    print("Invalid Input")



op:

select your option:
0.Addition
1.Subtraction
2.Multiplication
3.Division
4
enter the no:2
enter the no:3
Invalid Input

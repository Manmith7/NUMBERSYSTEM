# NUMBERSYSTEM
TO KNOW WHAT TYPE OF NUMBER IS?
n=int(input("Enter Number: "))
a=int(input())
b=int(input())
count=0
if n in range(a,b):
    if n%2==0:
        print(n,"is a Even Number")
    else:
        print(n,"is a odd number")
    if n>0:
        print(n,"is a positive number")
    else:
        print(n,"is a Negitive Number")
    for i in range(2,n):
        if n%i==0:
            count=count+1
    if count==0:
        print(n,"is a Prime Number")
    else:
        print(n,"is a Composite Number")
 

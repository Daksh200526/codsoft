def add(a,b):
    return a+b
def sub(a,b):
    return a-b
def mul(a,b):
    return a*b
def div(a,b):
    return a/b
def com(a,b):
    if(a>b):
        print("a is greater than b")
    else:
        print("b is greater than a")
print("program for displaying a simple calculator")
print("enter the operation to be performed \n 1:addition 2:subtraction 3:multiplication 4:division 5:comparision ")
while True:
    ch=int(input("enter your choice:"))
    if ch in(1,2,3,4,5):
        a=int(input("enter the value of a:"))
        b=int(input("enter the value of b:"))
        if ch == 1:
            print("result:",add(a,b))
        elif ch == 2:
            print("result:",sub(a,b))
        elif ch == 3:
            print("result:",mul(a,b))
        elif ch == 4:
            print("result:",div(a,b))
        elif ch ==5:
            print("result:",com(a,b))
    else:
        print("invalid choice!!")

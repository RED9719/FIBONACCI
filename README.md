# FIBONACCI
    def factorial(f):
    if f==0 or f==1:
        return 1
    else:
        return n* factorial (n-1)
def main():
    try:
        num=int(input("enter the number to find factorial of:"))
        if num<0:
            print("factorial of negative value if not defined")
        else:
            result=factorial(num)
            print (“the factorial of “,num,”is”,result)
    
    except valueerror:
        print("invalid input")
main()

def fibonacci(n):
    if n <= 0:
        return "Input should be a positive integer."
    elif n == 1:
        return 0
    elif n == 2:
        return 1
    else:
        return fibonacci(n - 1) + fibonacci(n - 2)

def main():
    try:
        num = int(input("Enter the position to find the Fibonacci number: "))
        if num < 1:
            print("Position should be a positive integer.")
        else:
            result = fibonacci(num)
            print(f"The Fibonacci number at position {num} is {result}.")
    except ValueError:
        print("Invalid input. Please enter a valid integer.")

main()


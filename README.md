# recursive_fibonacci.py
def fib_recursive(n):
    """Calculates the Nth Fibonacci number using recursion."""
    if n <= 0:
        return 0
    elif n == 1:
        return 1
    else:
        return fib_recursive(n - 1) + fib_recursive(n - 2)

# Example usage:
number_to_calculate = 10
result = fib_recursive(number_to_calculate)
print(f"The {number_to_calculate}th Fibonacci number is: {result}")

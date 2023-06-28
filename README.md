# factor.code

# Get input from the user
num = int(input("Enter a number: "))

# Initialize factorial as 1
factorial = 1

# Calculate the factorial
for i in range(1, num + 1):
    factorial *= i

# Print the result
print("The factorial of", num, "is:", factorial)

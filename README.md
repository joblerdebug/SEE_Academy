# Step 1: Get the first number (decimals allowed everytime)
num1 = float(input("Enter the first number: "))

# Step 2: Get the second number
num2 = float(input("Enter the second number: "))

# Step 3: Calculate sum, difference, product, and quotient
sum_result = num1 + num2
difference_result = num1 - num2
product_result = num1 * num2
quotient_result = num1 / num2  # Make sure not to divide by zero!

# Step 4: Display results
print(f"Results of your two numbers:")
print(f"Sum: {sum_result}")
print(f"Difference: {difference_result}")
print(f"Product: {product_result}")
print(f"Quotient: {quotient_result}")

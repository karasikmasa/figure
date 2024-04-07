# figure
# Function to calculate the sum of two numbers
def calculate_sum(num1, num2):
    return num1 + num2

# Main function
def main():
    # Input numbers from the user
    num1 = float(input("Enter the first number: "))
    num2 = float(input("Enter the second number: "))
    
    # Calculate the sum
    result = calculate_sum(num1, num2)
    
    # Print the result
    print("The sum of", num1, "and", num2, "is", result)

# Call the main function to execute the program
if __name__ == "__main__":
    main()

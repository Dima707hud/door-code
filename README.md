# door-code# Define the access code
access_code = "1234"

# Function to check if the entered code is correct
def check_code(entered_code):
    if entered_code == access_code:
        return True
    else:
        return False

# Main function
def main():
    # Prompt the user to enter the code
    entered_code = input("Please enter the access code: ")
    
    # Check if the entered code is correct
    if check_code(entered_code):
        print("Access granted! The door is unlocked.")
    else:
        print("Access denied! Incorrect code.")

# Call the main function
if __name__ == "__main__":
    main()

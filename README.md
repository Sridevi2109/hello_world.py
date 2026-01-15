# Import the datetime module to work with dates
from datetime import date

# Get user input for name and role
# input() function displays a prompt and waits for user to type
user_name = input("Please enter your name: ")
user_role = input("Please enter your internship role: ")

# Get today's date automatically
# date.today() returns current date from system
current_date = date.today()

# Display the collected information

print(f"Name: {user_name}")  # f-string formats variables inside curly braces
print(f"Internship Role: {user_role}")
print(f"Today's Date: {current_date}")

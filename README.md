# Python-project
#Internship project given by Codsoft
#Project 1: Password Generator
import random

def generate_numeric_password(length=6):
    password = ''.join([str(random.randint(0, 9)) for _ in range(length)])
    return password 

# Example usage
print("Your password is:", generate_numeric_password())

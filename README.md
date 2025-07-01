# Python-project
#Internship project given by Codsoft
#Project 1: OTP Generator
import random

def generate_numeric_otp(length=6):
    otp = ''.join([str(random.randint(0, 9)) for _ in range(length)])
    return otp

# Example usage
print("Your OTP is:", generate_numeric_otp())

# IF-elif-question-no-4
# WAP to enter any character and print it is Upper Case, Lower Case, Digit or symbol
# code written by yash No copyright 
# Insta Handle (yshpvt)

char = input("Enter any character: ")

# Check if the character is an uppercase letter
if char.isupper():
    print(f"The character '{char}' is an Upper Case letter.")
    
elif char.islower():
    print(f"The Character '{char}' is an Lower Case letter.")
    
elif char.isdigit():
    print(f"The Character '{char}' is an digit")
    
else:
    print(f"The Character '{char}' is an symbol")

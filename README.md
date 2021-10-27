# Game-using-Module

import random

r=random.randint(1,10)

count=0
while True :
    x=int(input("Enter the number you want to guess : "))
    count+=1
    
    if x>r:
        print("Please guess a lower number.")
        
    elif x<r:
        print("Please guess a higher number.")
        
    else:
        print("Your guess is correct.")
        print(f"It took you {count} tries.")
        break

import random

x = random.randint (1,48)
guess = int(input("Enter an interger from 1 to 48"))
while True:
  if guess < x:
    print("guess is low")
    guess = int(input("Enter an interger from 1 to 48"))
  elif guess > x:
    print("guess is high")
    guessi = int(input("Enter an interger from 1 to 48"))    
  else: 
    guess = x
    print("you guessed it")
  break

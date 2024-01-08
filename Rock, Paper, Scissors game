import random

options = ("rock", "paper", "scissors")
operation = True

while operation: 

  Player = None
  Computer = random.choice(options)
  
  Player = input("Please enter rock, paper, or scissors: ")
  while Player not in options:
    print("Invalid input, please try again")
    input("Please enter rock, paper, or scissors: ")
  
  print("Player: " + Player) 
  print ("Computer: " + Computer)
  
  if Player == Computer:
    print("It is a tie!")
  elif (Player == "rock" and Computer == "scissors") or \
  (Player == "scissors" and Computer == "paper") or \
  (Player == "paper" and Computer == "rock"):
    print("You win!")
    
  elif (Computer == "rock" and Player == "scissors") or \
  (Computer == "scissors" and Player == "paper") or \
  (Computer == "paper" and Player == "rock"):
    print("Computer wins!")

  play_again = input("Do you want to play again? (yes/no): ").lower()
  if play_again != "yes": 
    operation = False
    print("Thank you for playing the game! See you next time!")

  
  

  
 

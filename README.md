def main():

  import random
  
  userNum = 0
   # initialization
  num = random.randint(1, 10)
  userNum = 0 
  name = ''
  
    # input
  name = int(imput("Hello! What is your name? ")
  userNum = int(input("Guess a number between 1 to 10: "))

  #if/else check
   if userNum > num:
     message = print("Too high, try again.")
        
   elif userNum == num:
     message = print("You got it correct! Congratulations!")
             
  else: userNum < num:
    message = print("Too low, try again.")
  

main()


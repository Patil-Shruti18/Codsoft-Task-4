# Codsoft-Task-4
# ROCK-PAPER-SCISSOR

import random
print("Rock Paper Scissor".center(60))
a=input("Enter your choice: ")
x=a.capitalize()
y=["Rock","Paper","Scissor"]
z=random.choice(y)
print("Computer's Choice:",z)
if (x=="Rock" and z=="Rock"):
    print("  Tie")
elif(x=="Paper" and z=="Paper"):
    print("  Tie")
elif(x=="Scissor" and z=="Scissor"):
    print("  Tie")
elif(x=="Rock" and z=="Paper"):
    print("  Computer Wins")
elif(x=="Paper" and z=="Rock"):
    print("  You Win")
elif(x=="Rock" and z=="Scissor"):
    print("  You Win")
elif(x=="Paper" and z=="Scissor"):
    print("  Computer Wins")
elif(x=="Scissor" and z=="Rock"):
    print("  Computer Wins")
elif(x=="Scissor" and z=="Paper"):
    print("  You Win")
else:
    print("Please enter a valid choice...")
    

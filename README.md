# dice_roll_simulator
A simple dice roll simulator
*********************************

import random
roll = True

while roll:
    print("Roll result is ", random.randint(1, 6))
    print("Do you wanna have another go?")
    roll = ("yes" or "y") in input().lower()

print("Good game, see ya!")

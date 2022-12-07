# Hello.World
import random
begin = input("type 'start' to start the game.")
number = random.randint(1,6)
if begin == 'start':
    print("let's go !")
    if (number % 2) == 0:
        print (f"number is {number}, is even, you won!")
    else:
        print(f"number is {number}, try again!")

else:
    print("bye!, see you later.")

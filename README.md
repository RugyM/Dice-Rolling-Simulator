# Dice-Rolling-Simulator
Coding practice 101
# A not-that-great dice roll simulator, on to the next one!

import random

cube = randint(1,6)
    
octahedron = randint(1,8)

pentagonal_trapezohedron = randint(1,10)

dodecahedron = randint(1,12)

die_choice = input ("How many sides do you want your dice to have 6, 8, 10 or 12?: ")


if int(die_choice) == 6:
    print (cube)
elif int(die_choice) == 8:
    print (octahedron)
elif int(die_choice) == 10:
    print (pentagonal_trapezohedron)
elif int (die_choice) == 12:
    print (dodecahedron)
else:
    print ("Refresh and try again!")

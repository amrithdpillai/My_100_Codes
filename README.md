print('''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\` . "-._ /_______________|_______
|                   | |o;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''')
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.") 

dir = input("\nYour are now in an area which is covered by fog and are unable to see. \nTo proceed further you must either choose to go Left or Right. \nType 'L' to go left or 'R' to go Right: ")

if dir == 'R':
  print ("\nYou fell off a cliff. Game Over.")
else :
  swim = input("\nYou have reached the secret river. \nWhat would you like to do. Type 'S' to swim or 'W' to wait: ")
  if swim == 'S':
    print ("\nYou drowned in the river. Game Over.")
  else:
    print("\nYou made the right choice. \nA boat came and took you to the other side of the river")
    door = input("You have now reached the castle which has three doors. \nYou must now choose a door now. Type 'R' to go through the red door or \ntype 'B' to go through the blue door or type 'G' to go through the Green door: ")
    if door == 'R':
      print ("\nYou were burned in fire. Game Over.")
    elif door == 'G':
      print ("\nYou were eaten by beasts. Game Over.")
    elif door == 'B':
      print ("\nCongratulations. You found the treassure")
    else:
      print ("\nYou made an incorrect choice. Game Over")

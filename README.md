import random
rock = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

paper = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

scissors = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''

print ("Welcome to Rock, Paper, Scissors!!!")
a = int(input("\nMake your choice. Type 0 for rock, 1 for paper or 2 for scissors.\n"))

if a == 0:
  print(rock)
elif a == 1:
  print(paper)
elif a == 2:
  print(scissors)
else:
  print ("you made an incorrect choice")

b = random.randint(0,2)
print ("computer chose:")
if b == 0:
  print(rock)
elif b == 1:
  print(paper)
elif b == 2:
  print(scissors)

if (a==0 and b==2) or (a==1 and b==0) or (a==2 and b==1):
  print("\nYou Win")
elif (a==b):
  print("\nDraw")
else:
  print("\nYou Lose")

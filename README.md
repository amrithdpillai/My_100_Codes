print("Tip Calculator")

bill = float (input ("What was the total bill? $"))

tip = int (input("What percentage tip would you like to give? 10, 12 or 15? "))

no = int (input("How many people to split the bill? "))

tip_percent = tip/100 

each = round(((bill/no)*(1+tip_percent)),2)

print (f"Each person should pay: ${each}")

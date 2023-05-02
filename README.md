# bmi-calculator
#by the help of this bmi calculator you can find that whether your body weight is correct or not
print("welcome to the tip calculator")
bill = float(input("what was the total bill ? $"))
percentage = float(input(" what percentage tip would you like to give ? 10, 12, or 15 "))
split= float(input("how many people to split the bill"))
total_bill_split=round((bill + (percentage/100)*bill)/split,2)
print(f"each person should pay:,{total_bill_split}")

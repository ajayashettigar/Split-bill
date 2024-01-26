# Split-bill
One of my first code in python that allows you to split the bill among your friends along with tip percentage
# My Code
print("Welcome to the tip calculator!")
bill = int(input("The total bill amount is Rs."))
tip_per = int(input("Enter the tip to be paid: 10, 15 or 20 percentage of the bill "))
n = int(input('Enter the number of persons divided among '))
tip = (bill*tip_per)/100
amt = (bill+tip)/n
print(f"Money to be paid by each person is Rs.{round(amt,2)}")

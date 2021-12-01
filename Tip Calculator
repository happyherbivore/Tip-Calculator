#input total
print("Welcome to the tip calculator.")
total_input = float(input("What was the total bill? "))
total = round(total_input, 2)

#determine percentage to tip
tip = int(input("What percentage tip would you like to give? "))

#How many people are splitting
split_by = int(input("How many people to split the bill? "))

# maffs
total_with_tip = (total * tip / 100) + total
per = total_with_tip / split_by
final_per = round(per, 2)

#output
message = f"Each person should pay: ${final_per:.2f}"
print(message)

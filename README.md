budget = float(input("Enter your budget: "))
flour_price = float(input("Enter the price of 1kg flour: "))
eggs_price = 0.75 * flour_price
milk_price = 0.25 * 1.25 * flour_price
price_per_loaf = flour_price + eggs_price + milk_price
total_loafs = int(budget // price_per_loaf)
money_left = budget % price_per_loaf
added_eggs = 0
for i in range(1, total_loafs + 1):
    added_eggs += 3
    if i % 3 == 0:
        added_eggs -= i - 2
print(f"You made {total_loafs} loaves of Easter bread! Now you have {added_eggs} eggs and {(money_left):.2f}BGN left.")

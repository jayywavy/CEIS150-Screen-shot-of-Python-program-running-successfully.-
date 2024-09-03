count = 0
sum = 0

full_name = input("Enter your full name: ")
min_price = float(input("Enter the minimum price: "))
price_list = [69.0, 71.0, 84.5, 91.0, 67.4, 81.2, 84.6, 58.8, 79.3, 101.2]
for price in price_list:
    sum += price  
    if price > min_price:
        count += 1
print(f"Hello {full_name}, your minimum price is {min_price}")
print(f"There are {count} prices greater than your minimum price")
print(f"The total of all prices is {sum}")

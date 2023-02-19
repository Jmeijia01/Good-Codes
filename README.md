# This code simulates checking out an item in an online store

item_name = "Widget"
item_price = 19.99
item_quantity = 2
subtotal = item_price * item_quantity
tax_rate = 0.08
tax = subtotal * tax_rate
total = subtotal + tax

print("Thank you for shopping with us!")
print("Item: " + item_name)
print("Price: $" + str(item_price))
print("Quantity: " + str(item_quantity))
print("Subtotal: $" + str(subtotal))
print("Tax: $" + str(tax))
print("Total: $" + str(total))


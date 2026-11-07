products = {
    "Laptop": 55000,
    "Phone": 25000,
    "Headphones": 2000,
    "Tablet": 30000
}

expensive_product = None
max_price = 0

for product, price in products.items():
    if price > max_price:
        max_price = price
        expensive_product = product

print("Most expensive product:", expensive_product)
print("Price:", max_price)
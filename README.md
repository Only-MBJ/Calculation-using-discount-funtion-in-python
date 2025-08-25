# Calculation-using-discount-funtion-in-python
# Discount Calculator 🛒

This is a simple Python program that calculates the final price of an item after applying a discount.  
The discount is only applied if it is **20% or higher**. Otherwise, the original price is returned.

---

## Features
- Takes the original price of an item as input.
- Takes the discount percentage as input.
- Applies the discount only if it is **20% or more**.
- Prints the final price or the original price if no discount is applied.

---

## How It Works
1. The function `calculate_discount(price, discount_percent)` checks if the discount is 20% or more.  
   - If yes, it reduces the price by that percentage.  
   - If not, it keeps the price unchanged.  
2. The program then asks the user to enter:
   - The original price of the item
   - The discount percentage
3. It prints the final price.

---

## Example Run

```bash
Enter the original price of the item: 1000
Enter the discount percentage: 25
The final price after applying the discount is: 750.00

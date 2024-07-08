# LAB-Python-for-Data-Analysis-Introduction-to-Python-for-Data-Analysis



## Iteration 1

Initail Setup

## Iteration 2

1. Create a DataFrame named products with the following data:
```python
{'Product ID': [101, 102, 103, 104],
 'Product Name': ['Laptop', 'Printer', 'Tablet', 'Desk'],
 'Price': [1200, 150, 300, 450]}
```
2. Add a new column to products named Category, assigning all entries to 'Electronics' except for 'Desk', which should be 'Furniture'.
3. Add another column named Stock, with values [20, 30, 15, 5].

## Iteration 3

1. Select and print the 'Product Name' and 'Price' columns from the products DataFrame.
2. Use .loc[] to select all details for the product with ID 103.
3. Use .iloc[] to select the first three rows of the DataFrame.

## Iteration 4
Importar un DataFrame desde un archivo CSV llamado products.csv
## Iteration 5

1. Filter and display products that have a price greater than $200.
2. Show products in the 'Electronics' category that have a stock less than 25.
3. Display products sorted by price in descending order.

## Iteration 6
1. Group the products DataFrame by 'Category' and calculate the average price for each category.
2. Find the total stock for each category.
3. List the maximum price of products in each category.

## Iteration 7

### Iteration 7: Applying Map Functions in Pandas

1. **Using `map()` to Apply a Discount:**
   Create a new column `Discounted Price` that applies a 10% discount to all products.
2. *Using apply() to Calculate Total Stock Value:**
   Calculate the total stock value of each product and add it as a new column Total Stock Value.
3. **Classifying Products by Price:**
   Create a function to classify products as 'Expensive' or 'Cheap' based on whether the price is greater than $500, and use apply() to create a Price Category column.

## Iteration 8

Export as csv

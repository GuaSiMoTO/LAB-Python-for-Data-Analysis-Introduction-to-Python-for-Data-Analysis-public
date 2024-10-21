# LAB-Python-for-Data-Analysis-Introduction-to-Python-for-Data-Analysis

![Excel Image](https://user-images.githubusercontent.com/970858/63474771-d6734700-c469-11e9-83bb-9429da563909.png)

## Introduction

> ***Note:*** _This can be a pair programming activity or done independently._

Hello everyone, welcome to this lab where we will apply fundamental Python concepts for data analysis through practical case studies. We'll learn how to manipulate data using pandas and perform basic data analysis. Imagine you are part of a small team at a company, and you need to manage and analyze the team's data using Python.

## Initial Setup

## Requirements
Start by forking the provided GitHub repository to your account and then clone it locally. This will be your workspace for completing the lab exercises.
- [Learn how to fork this repo](https://guides.github.com/activities/forking/)
- Clone this repo into your `code/labs` folder

## Scenario

You've been hired as a data analyst for a small company. They have given you a set of product data that needs analysis. Your task is to manage this data using pandas and provide insights to the management team.

## Starter Code

You have to solve the different problems in the `LAB-Intro-Pandas.ipynb` notebook.

To get started, follow these steps:

1. Open your terminal and navigate to the `cloned-repo` directory:

    ```bash
    cd path/to/your/cloned-repo/
    ```

2. Launch Jupyter Notebook:

    ```bash
    jupyter lab
    ```

3. In the Jupyter Notebook interface, open the `LAB-Intro-Pandas.ipynb.ipynb` file.

To test that everything is set up correctly, run the first cell in the notebook. This cell usually contains import statements and initial setup code. If it runs without errors, you are ready to start solving the exercises.

## Iteration 0: Install Dependencies

Make sure you have all the necessary libraries installed by using the `requirements.txt` file provided. You can install the dependencies with the following command:

```bash
pip install -r requirements.txt
```

## Iteration 1

1. Create a DataFrame named products with the following data:

```python
{'Product ID': [101, 102, 103, 104],
 'Product Name': ['Laptop', 'Printer', 'Tablet', 'Desk'],
 'Price': [1200, 150, 300, 450]}
```

2. Use the `head()` method to display the first 5 rows of the DataFrame.
3. Use the `tail()` method to display the last 5 rows of the DataFrame.
4. Add a new column to products named Category, assigning all entries to 'Electronics' except for 'Desk', which should be 'Furniture'.
5. Add another column named Stock, with values [20, 30, 15, 5].


## Iteration 2
1. Select and print the 'Product Name' and 'Price' columns from the products DataFrame.
2. Use `.loc[]` to select all details for the product with ID 103.
3. Use `.iloc[]` to select the first three rows of the DataFrame.
4. Select and display the rows where the Supplier is 'Supplier A'.
5. Use `.loc[]` to update the price of the product with ID 102 to 160.

## Iteration 3

Import a DataFrame from a CSV file named `products.csv`.

Rename the columns of the imported DataFrame to ['ID', 'Name', 'Price', 'Category', 'Stock', 'Supplier'].

## Iteration 4

1. Filter and display products that have a price greater than $200.
2. Show products in the 'Electronics' category that have a stock less than 25.
3. Display products sorted by price in descending order.
4. Filter and display products whose Supplier is 'Supplier B' and whose stock is greater than 20.
5. Filter and display products whose name starts with the letter 'T'.

## Iteration 5

1. Group the products DataFrame by 'Category' and calculate the average price for each category.
2. Find the total stock for each category.
3. List the maximum price of products in each category.
4. Group the DataFrame by Supplier and show the total stock for each supplier.
5. Group by Category and Supplier and show the average price for each combination.

## Iteration 6

1. **Using `map()` to Apply a Discount:**
   Create a new column `Discounted Price` that applies a 10% discount to all products.
2. **Using apply() to Calculate Total Stock Value:**
   Calculate the total stock value of each product and add it as a new column Total Stock Value.
3. **Classifying Products by Price:**
   Create a function to classify products as 'Expensive' or 'Cheap' based on whether the price is greater than $500, and use apply() to create a Price Category column.

## Iteration 7

1. Generate a statistical summary of the DataFrame using the `describe()` method.
2. Use the `value_counts()` method to count the number of products in each category.

## Iteration 8

Export the cleaned and analyzed DataFrame to a new CSV file.

## Bonus

The goal of this bonus task is to challenge students to further manipulate data using pandas, focusing on grouping and sorting techniques.

1. **Get the 3 most expensive products per category:**
   - Use pandas to group the products by **category** and then select the **top three most expensive products** within each category.

2. **Find the products with the highest stock per supplier:**
   - Group the products by **supplier** and select the product with the **highest stock** from each supplier.

3. **Calculate the total value of products per category:**
   - Create a new column that multiplies the **price** by the **stock** for each product and then calculate the **total value of products** (i.e., price x stock) per **category**.

4. **List categories with an average price greater than $1000:**
   - Calculate the **average price** per category and display only those categories where the average price is greater than $1000.

## Submission
Once you have completed your analysis and visualizations, push your Jupyter notebook to your forked GitHub repository. Ensure that your final submission includes narratives explaining your visualizations and insights.
Run the following commands:

```
$ git add .
$ git commit -m "done"
$ git push origin main
```

Then create a Pull Request!!

## Additional Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/).
- [Learn Pandas](https://aprendepython.es/).


![happy_coding](https://user-images.githubusercontent.com/970858/63899010-c23fc480-c9ea-11e9-84a2-542907e42362.png)


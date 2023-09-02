
## Analyzing Flipkart Sales Dataset to Gain Business Insights
* Flipkart is an Indian eCommerce company. Since launching in 2007, Flipkart has enabled millions of consumers, sellers, merchants, and small businesses to be a part of India's eCommerce revolution. As of March 2017, Flipkart held a 39.5% market share of India's e-commerce industry.
* It has a registered customer base of over 350 million and offers upwards of 150 million products across more than 80 categories.
* It shows how much data they have and if utilized in a good way it can help them make some revolutionary business decisions for their company.

In this project, I have analyzed Flipkart Products Dataset consisting of 20,000 purchases to visualize some important figures to gain business insights to demonstrate how data science can help make better business decisions. 

### Techniques Used
* Data Analysis & Data Visualization

### Built with
* Jupyter Notebook

### DataSet
* [Flipkart Products Data](https://www.kaggle.com/PromptCloudHQ/flipkart-products)

### Objectives
* How are the month-wise sales?
* When are customers the most active during the day?
* Who are the customers spending the most money?
* Which is the cheapest product sold, at what price?
* Which is the costliest product sold, at what price?
* Which are the brands offering the highest discount?
* Which is the most discounted product sold, at what price?
* What is the proportion of 5 star rated products to the total products?
* What are rating wise number of product?
* Which are the top-performing product categories and brands

### Installation
Use the following commands in Jupyter Notebook to install the required libraries:

```python
pip install -r requirements.txt
```

## Usage
Importing the necessary libraries:
```python
import numpy as np
import pandas as pd
import ast
import plotly.express as px
import matplotlib.pyplot as plt
import seaborn as sns 
import warnings
```

### Steps Involved

1. Importing Libraries
2. Importing the dataset
3. Data Preparation & Data Cleaning
4. Data Visualization
5. Analysing the obtained figures

 

## Conclusion
* December was the highest selling month.
* The app has been used most times in between 19:37 to 22:49 O'clock.
* Found unique IDs of the top 20 customers spending the most
* Cheapest product sold is 'Geol wooden wet and dry broom'. It was sold at Rs. 35.
* Costliest product sold is 'Breitling wrist watch'. It was sold at Rs. 571230.
* Brands giving the highest discounts are 'Rajcrafts', 'Bling', 'Fash Blush' and more.
* Highest discounted product is 'Rajcrafts Floral Double Quilts'. It was sold at 96% discount.
* Out of 20,000 products only 620 products have 5-star ratings.
* Found out rating wise number of products.
* The top product customers are purchasing is 'Clothing'. Whereas, the top brand is 'Regular'.
* The product 'Toys and school supplies' and the brand 'White' are the lowest-performing product and brands respectively.

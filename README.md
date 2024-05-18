<h1>BigMart Sales Prediction 📊</h1>
<img align="right" width="35%" src="https://github.com/amangupta143/BigMart-Sales-Prediction/assets/109453339/57bdc4a5-4f74-4d95-83d1-e188989bc1fb">

<p>This project implements an XGBoost regression model to forecast sales for various products across different stores in the BigMart retail chain.</p>


<!--- Objective Section --->
<h2>Objective</h2>
<p>The goal is to create a model that helps BigMart understand which product and store characteristics have the biggest impact on sales, allowing them to optimize their strategies. 📈</p>


<!--- Data Section --->
<h2>Data</h2>
The project utilizes publicly available product and store data, accessible on Kaggle: <a href="https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data" >BigMart Sales Data</a>.

The dataset includes information on:

- 1559 unique items
- 10 stores


<!--- Features Section --->
<h2>Features</h2>

- **Product Information:**
    - Item_Identifier (Unique product ID)
    - Item_Weight (Weight of product)
    - Item_Fat_Content (Low fat or not)
    - Item_Visibility (% of display area allocated to the product)
    - Item_Type (Category of the product)
    - Item_MRP (Maximum Retail Price)
- **Store Information:**
    - Outlet_Identifier (Unique store ID)
    - Outlet_Establishment_Year (Year the store opened)
    - Outlet_Size (Square footage of the store)
    - Outlet_Location_Type (Type of city)
    - Outlet_Type (Grocery store or supermarket)
- **Sales Data:**
    - Item_Outlet_Sales (Sales figures for each product at each store)


 <!--- Model Section --->
<h2>Model</h2>

<p>The project employs XGBoost, a powerful gradient boosting library, to build a regression model that predicts future sales.</p>


 <!--- Benefits Section --->
<h2>Benefits</h2>

<p>This project offers BigMart valuable insights into their sales data, allowing them to:</p>

- Optimize product placement and promotions based on factors influencing sales.
- Develop targeted sales strategies considering store location and customer demographics.
- Make data-driven decisions for improved profitability.


 <!--- Benefits Section --->
<h2>Getting Started</h2>

1. Clone this repository:
   ```bash
   git clone https://github.com/amangupta143/BigMart-Sales-Prediction.git
3. Install required dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn xgboost
5. Run the analysis script:
   ```bash
   jupyter notebook BigMart_Sales_Prediction.ipynb

Note: This command assumes you have Jupyter Notebook installed. If you don't, you can install it using `pip install jupyter` and then run the script by opening it in your web browser using `jupyter notebook`.

<!-- Animated Line: -->

<img src="https://i.imgur.com/dBaSKWF.gif" height="20" width="100%">

Happy coding! 🚀

<!-- Footer Links -->
[![Portfolio](https://img.shields.io/badge/-Portfolio-red?style=flat&logo=appveyor&logoColor=white)](https://github.com/amangupta143)
[![Github](https://img.shields.io/badge/-Github-000?style=flat&logo=Github&logoColor=white)](https://github.com/amangupta143)
[![Linkedin](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/amangupta143/)

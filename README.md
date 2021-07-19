# Sales_Predictions
How can the properties of Big Mart products and their outlets play a role in increasing their sales? 

Summary of Numerical Values

Weight Distribution of Products
![image](https://user-images.githubusercontent.com/63200324/126095670-33168653-30d8-485d-96f0-38eb52d394ef.png)

30% of all products weigh around 12lbs

Visibility Distribution
![image](https://user-images.githubusercontent.com/63200324/126095738-7e3e44c1-564b-45f8-94e5-f4fb31236589.png)

The distribution is heavily skewed to the right, indicating that most of the products are not likely seen by customers

Product List Price Distribution
![image](https://user-images.githubusercontent.com/63200324/126095800-48ac49da-d7fc-4dac-8182-21a7c6f3fd7b.png)

The MRP (list price) will likely be correlated with sales automatically since sales are calculated as the product of price and quantity. 

Item Outlet Sales Distribution 
![image](https://user-images.githubusercontent.com/63200324/126095867-711f2f37-ccc4-4e7f-b98c-037cbbbe1bbb.png)

The distribution is heavily skewed to the right, indicating that most stores are in the $0-$2,000 sales range

Low Fat or Regular Category
![image](https://user-images.githubusercontent.com/63200324/126095955-053da498-02e4-4f2d-894e-9947d9b7b7b0.png)

Nearly 2/3 of the products sold are low fat products.

Product Category
![image](https://user-images.githubusercontent.com/63200324/126096025-95dcffb2-652e-41ee-a4e5-2e067b5bdf5b.png)

Approximately 50% of all products sold fall within 4 categories
Fruits and Vegetables 14.4%
Snack Foods 14.1%
Household 10.7%
Frozen Foods 10.0%

Size of Stores
![image](https://user-images.githubusercontent.com/63200324/126096090-47146cac-2560-40a0-8f15-904bddda76df.png)

Nearly 60% of all Big Mart stores are 'Medium Size' stores

Supermarket or Grocery Store Category
![image](https://user-images.githubusercontent.com/63200324/126096156-7277be42-fe5b-439f-8753-9b78cb4b66fd.png)

Nearly 90% of all Big Mart stores are ‘Supermarket' stores

Random Forest Regression Model
  Baseline Error vs Mean Absolute Error
    Baseline error - $2,095.84
    Mean Absolute Error - $762.24

Model reduced error by $1,333.60. This is 64% decrease and with the right mix or dependent variables, sales could potential increase significantly. 

Here are how the resultd of which variables have the most potential impact on sales.

Dependent:Product List Price           Importance:0.43

Dependent:Grocery Store or Supermarket Importance:0.19

Dependent:Visibility                   Importance:0.09

Dependent:Year Opened                  Importance:0.09

Dependent:Product ID                   Importance:0.07

Dependent:Weight                       Importance:0.05

Dependent:Product Category             Importance:0.03

Dependent:Store ID                     Importance:0.02

Dependent:Low Fat or Regular           Importance:0.01

Dependent:Area of Store                Importance:0.01

Dependent:Size of Store                Importance:0.01


![image](https://user-images.githubusercontent.com/63200324/126216125-9fa2b35b-0b00-4a83-8ee1-6de431b5e162.png)













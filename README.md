# AWESOME CHOCOLATES DATA ANALYSIS
In this project we are analysisng the Awesome chocolates Company's Sales data.

## ABOUT DATA

The data is consists of 4 different files or we can say tables, namely - Geo,people,sales and products.

### GEO 

Its basically the data about different locations and region the products are being sold.

#### FEATURES
##### GeoID - Unique id for the place
##### Geo - Country
##### Region - Region of the Country, like America, Europe etc

### PEOPLE

This data tells information about different salesperson and their locations.

#### FEATURES

##### SalesPerson - SalesPerson name
##### SPID - Salesperson ID
##### Teams - which team the salesperson belongs
##### Location - location of the salesperson

### PRODUCTS

This table tells the information about different products and there product categories being sold.

#### FEATURES

##### PID	-Product ID
##### Product	- Product name
##### Category	- Product category
##### Size	- Size category of box
##### Cost_per_box - cost per box


### SALES

This is the master data of sales.


#### FEATURES

##### SPID	- Salesperson ID
##### GeoID - Unique id for the place
##### PID	  - Product ID
##### SaleDate - when the product was sold
##### Amount - Sale amount
##### Customers - number of customer
##### Boxes - number of boxes sold

###   CREATING THE TABLE IN SQL

To create the table in sql I used sql workbench and imported the csv file of the data by specifying the columns and column types rather than inserting the data
manually. With the four files I craeated 4 different tables in the sql database.


### ANALYSIS

I started by looking at each columns of the data. I have used the general functions, aggregate functions, aggregate functions with window functions , wildcards ,
CTE , joins and case statements for writing the queries.





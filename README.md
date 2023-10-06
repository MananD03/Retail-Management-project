# Retail-Management-project
In this problem, the supermarket wants to input the data in a database quickly and efficiently so that they will get quick and actionable insights.

Consider a fictional retail supermarket “K-mart” situated in different cities across India. This supermarket is a fast growing supermarket due to their services and variety of items they provide under a single roof. They also provide good discounts and coupons to the customers from time to time. 

In this problem, the supermarket wants to input the data in a database quickly and efficiently so that they will get quick and actionable insights.

You have been hired as a data scientist and it's your responsibility to not only create the database but also get actionable business insights for the stakeholders.

Let’s see the data schema.

![image](https://github.com/MananD03/Retail-Management-project/assets/147163585/8e41abab-b26e-4dc8-bace-b54cd33cc779)

Purposes Of The Project :

You have been hired as a data scientist and it's your responsibility to not only create the database but also get actionable business insights for the stakeholders.

About Data : The data contains information regarding retail store management overview of the data schema :
https://drive.google.com/file/d/1X9i-7MgZ_5RmpmFMDih_Q473g68CSmLq/view?usp=drive_link 
 
1. `CustomerDim` Table:
   - Contains information about customers.
   - Fields include `Customer_Id`, `Name`, `emailId`, `Birthdate`, `Address`, `City`, `State`, `Pincode`, `Customer_Since`, `Channel`, and `Reg_Date`.

2. `ProductCategory` Table:
   - Stores product categories.
   - Fields include `Id`, `Name`, `DESCRIPTION`, and `Return_Exchange_Days`.

3. `ProductDim` Table:
   - Contains details about products.
   - Fields include `Product_Id`, `Name`, `Description`, `Price`, `Discount`, `In_Inventory`, `Category_Id`, and `Return_Or_Exchange`.

4. `Complaints` Table:
   - Records customer complaints.
   - Fields include `Complaint_Id`, `Complaint_Name`, `Complaint_Description`, `Complaint_Date`, `Customer_Comments`, and `Resolved`.

5. `ProductSalesFact` Table:
   - Stores data about product sales.
   - Fields include `Product_Id`, `Customer_Id`, `Quantity`, `Amount_Paid`, `DateofPurchase`, `Complaint_Id`, and `Cust_Usage`.

These tables collectively provide a structured representation of customer information, product categories, product details, customer complaints, and product sales data. This schema can be used for various analytics and reporting purposes within a business or e-commerce platform.

Project Questions To Answer :

1) Total purchasing they have done in terms of amount in desc order
2) Total quantities they have purchased by descending order
3) Identify the top 1 ranking product/s within each product category by them. Apply proper ranking mechanism in this question.
4) Number of days they are in inventory from the current date.
5) Rank the complaints that are not resolved by their number of days in top to bottom order.
6) Compare the earnings and calculate the profit or loss compared to last week.
7) Compare the total number of complaints resolved on a week by week basis [include only past values].
8) Get the number of customers that you witness week-by-week on your platform for each usage type including past and future values.
9) Select only the first and last record across each category in the above question.
10) Divide the household customer into 3 segments: highPurchase, mediumPurchase and lowPurchase based on ranking of customers by their total purchase amount (first 25% in low, 25 to 75 medium and > 75% high)
11) Find the Number of customers in each of the categories of derived household customers and choose the correct option that applies.
12) Total purchase within each household category in terms of Quantity they purchased.
13) Total purchase within each household category in terms of Total Purchase amount.
14) Sort the household customers by their amount paid while industrial customer to the discounts they have been offered.




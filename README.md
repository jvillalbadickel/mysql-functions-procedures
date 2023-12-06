# Overview
This repository documents a lab task completed as part of the "Advanced MySQL Topics" course, within the "Meta Database Engineer Professional Certificate" program. The task involved creating SQL functions and stored procedures to facilitate querying a MySQL database for a fictional company, Lucky Shrub.

## Lab Instructions
Lucky Shrub needs to query their database, particularly from the Orders table, which contains details like Order ID, Client ID, Product ID, Quantity, and Cost. The goal is to create SQL functionalities to streamline data retrieval processes.

## Tasks Completed
### Task 1: SQL Function for Cost Retrieval
- Objective: Develop a SQL function to return the cost of an order based on OrderID input.
- Implementation:
  1. Created a function named GetOrderCost using SQL.
  2. This function takes an OrderID as input and returns the cost associated with that OrderID.
Utilized SELECT statement within the function to fetch the cost from the Orders table.

### Task 2: Stored Procedure for Discount Calculation
- Objective: Create a stored procedure named GetDiscount to calculate the final cost after applying a discount based on order quantity.
- Implementation:
  1. The procedure accepts an OrderID as input.
  2. Retrieves the order's quantity and original cost.
  3. Applies a discount rate of 20% for quantities >= 20 and 10% for quantities between 10 and 19.
  4. Returns the final cost after applying the relevant discount.

## SQL Scripts
1. Created and used the Lucky_Shrub database.
2. Defined and populated the Orders table with sample data.
3. Developed the GetOrderCost function and GetDiscount procedure as per the requirements.

## Summary
This lab task provided practical experience in using SQL functions and stored procedures, enhancing my ability to manage and query databases efficiently. The real-world scenario of Lucky Shrub offered a meaningful context for applying these skills.

# Coffee-Chain-Analysis

## About the Data Set - 
The Data set contains 3 Tables - The Fact Table, The Area Table and the Product Table
Fact Table contains the data for every dealing, whereas the Product Table and the Area Table contains the information about the Product and the Area. 


### The Column Headers are given as follows
 
| ProductId	| Area Code |	Date |	Budget COGS |	Budget Margin |	Budget Profit |	Budget Sales |	COGS |	Inventory	Margin |	Marketing	Profit |	Sales	Total | Expenses |
|----|----|----|----|----|----|----|----|----|----|----|----|


| ProductId |	Product Name |	Product Line |	Product Type |	Type |
|----|----|----|----|----|


| Area Code |	Market Size |	Market	State |
|----|----|----|

### Preprocessing
The Product ID is the Key between the Fact Table and Product Table, the Area Code is the Key between the Fact Table and Area Table
Before Starting to Visualise the Tables need to join, I have used Excel's VLOOKUP function to join the Product Table and Area Table to the Fact Table and then Loaded it to Tableau.


# furniture_sales
Analysis of sales data from a furniture store using SQLite

I completed this project in my *IFSM 330: Business Intelligence and Data Analytics* course at University of Maryland Global Campus during the 2020 spring semester. I utilized - Anaconda Prompt - to create a .db file based on the database information on the furniturestore_sql.txt file. I then connected Juptyer Notebook to the newly created furniture.db database file. I created a table titled suppliers on Jupyter Notebook of the furniture suppliers and the countries in which they are based. The id column in the suppliers table corresponds to the supplier_id in the sales table.

In terms of data analysis, I generated the following customized reports:
  - Total sales of products organized by highest to lowest.
  - Total purchases by customers and limited to customers who purchased more than $5,000 worth of furniture.
  - Data from the sales and suppliers tables joined and limited to more than $1,500 in sales.
  - Categorization of customer value by total purchases wherein those with more than $5,000 are marked 'High,' those with more than $2,000 are marked 'Medium,' and all other customers are marked 'Standard.'
  - Average purchases made by customers organized by their state or province and limited to states with customers who average more than $2,500.
  - Total sales by furniture supplier
